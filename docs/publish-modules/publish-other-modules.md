# Publish other LoopBack modules 

## Pre-requisite

1. You need to be on the [`loopback-openjsf` organization on npmjs](https://www.npmjs.com/settings/loopback-openjsf/teams), and part of the `developers` team. Contact the TSC memebers for access.

2. Install [`strong-tools`](https://www.npmjs.com/package/strong-tools), we'll be using the `slt-release` command to publish.

## Steps to publish

1. git clone the repo
2. log into npmjs using `npm login` command
3. run `slt-release -up <major/minor/patch>`. To determine which of major/minor/patch to choose, see https://semver.org/
4. after the release, you can run `npm view <module-name>` to check.
5. when you're done, as best practice, logout of NPM using `npm logout` to mitigate against accidental publishing and token stealing.



## How to revert the release
In case you want to revert the release, e.g. release the wrong semver-major/minor/patch, here are the steps:

1. Unpublish from npmjs 

   _Originated from https://www.npmjs.com/policies/unpublish_
   
   Run:
   `npm unpublish <package_name>@<version> to remove a specific version`

   Note: Once package@version has been used, you can never use it again. You must publish a new version even if you unpublished the old one
   
   You can verify the package is unpublished by running `npm view <package_name>`. 
   
2. Remove git tag
   
   _Originated from https://stackoverflow.com/questions/5480258/how-to-delete-a-git-remote-tag_
   
   After you've released, a new git tag is created. You can find that out from the repo page > Releases, for example, https://github.com/strongloop/loopback-datasource-juggler/releases.
   
   `git push --delete origin <tagname>`
   If you also need to delete the local tag, use:

   `git tag --delete <tagname>`

3. Revert the changes in `CHANGES.md`
   
   - You can check the latest changes by running `git show`. 
   
   - To revert, run `git revert HEAD`.
   
     Note: you might want to edit the commit message stating that it was released accidentally so that maintainers/users know why we're reverting it.  
    
   - Push changes, `git push`. 
   