# Publish LoopBack Modules

## Pre-requisite

You need to be on the [`loopback-openjsf` organization on npmjs](https://www.npmjs.com/settings/loopback-openjsf/teams), and part of the `developers` team. 

Contact the TSC memebers for access.

## Publish `loopback-next` monorepo

Since `loopback-next` is a monorepo, the steps to publish is a bit different from the rest of the modules.

Here are steps to publish:
1. git clone the repo

    ```sh
    $ git clone https://github.com/loopbackio/loopback-next.git
    ```
    Note: This step could be optional. Git cloning the repo again can make sure we have only the things from GitHub

2. log into npmjs

    ```sh
    $ npm login
    ```
    and then follow the prompt to login.

3. Run the publish command

    In the `loopback-next` folder, run the following commands:
    ```
    $ npm i 
    $ npm run release
    ```

4. Post an announcement on [#general Slack channel](https://loopbackio.slack.com/archives/CE8CRBBFU).
Note: Only Workspace Admin in LoopBack Slack workspace can post messages. Currently LoopBack TSC members have admin rights. 

### Release cadence

Roughly monthly release at the middle of the month. 

### Troubleshooting

1. When there are a subset of modules being published due to Lerna publish failures, what should I do to publish the rest? 

    You can run the following 2 commands:
    - `git reset --hard`.  At this point, there are files being updated but not pushed to git. 
    
    - `npx lerna publish from-package`. After running this command, you'll see the list of modules not being published yet. 

## Publish other repos

Pre-requisite: install [`strong-tools`](https://www.npmjs.com/package/strong-tools), we'll be using the `slt-release` command to publish.

Here are the steps to publish:

1. git clone the repo
2. log into npmjs using `npm login` command
3. run `slt-release -up <major/minor/patch>`. To determine which of major/minor/patch to choose, see https://semver.org/
4. after the release, you can run `npm view <module-name>` to check.

## Logging out after publishing

As best practice, logout of NPM using `npm logout` to mitigate against accidental publishing and token stealing.