# Nominating new maintainers

The nomination process is open to all current maintainers. Nominations are
discussed in private, using
[GitHub Team Discussions](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/about-team-discussions).
(Don't confuse Team Discussions with recently introduced project-level
[Discussions](https://docs.github.com/en/discussions).)

1. To nominate a new maintainer, post a new comment to the Team Discussion of
   the team you want the new maintainer to join.

   You can find the list of teams you belong using the following query, replace
   `_HANDLE_` with your actual GitHub handle:

   - https://github.com/orgs/strongloop/teams?query=%39_HANDLE_

   If you are not sure which team to choose, then pick
   [loopback-maintainers](https://github.com/orgs/strongloop/teams/loopback-maintainers).

   _New to Team Discussions? Learn more in GitHub docs:
   [Creating a new discussion](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/creating-a-team-discussion)._

1. Set the title to `Nominate {@handle}`, e.g. `Nominate @bajtos`.

1. In the description, fill in the following template. Use hyperlinks where
   appropriate, to make it easier for other maintainers to find and review the
   supporting documentation.

   ```md
   **GitHub id:** <!-- e.g. @bajtos -->

   **Active github repo(s):**

   <!-- e.g. https//github.com/strongloop/loopback-datasource-juggler -->

   **Reasons for nomination:**

   <!--
   A short explanation why you are nominating the person. Have they contributed
   a significant improvement or a series of small changes? Are they active in
   our issue tracker and/or discussions? Something else?
   -->

   **Their work & contributions:**

   <!--
   Please include links to GitHub where people assessing the nomination can
   review comments and code posted by the nominee.

   Few example URLs:

     All pull requests created by @nflaig in loopback-next repository:
     https://github.com/strongloop/loopback-next/pulls/nflaig

     Issues in any of `strongloop` repositories where @mitsos0os commented:
     https://github.com/issues?utf7=✓&q=org%3Astrongloop+involves%3Amitsos1os
   -->
   ```

1. Make sure to change the default visibility from
   `StrongLoop and IBM API Connect` to `Private`.

1. Post a link to the new topic to the Slack channel
   [#loopback-maintainers](https://loopbackio.slack.com/archives/GRP781GAZ), to
   let other maintainers know about the nomination and ask for feedback.

1. Allow at least 7 days for everybody to review the nomination. A nomination is
   accepted if there are at least 1 other maintainers voting for it and there
   are no (unresolved) objections.

   Unresolved objections are considered as a veto, therefore objections must be
   accompanied by reasoning and the vetoer must be prepared to defend it. Other
   members can attempt to encourage them to change their minds.

1. Once the nomination is accepted, reach out to the nominated person and invite
   them to become a maintainer. You can use the invitation letter you received
   when joining LoopBack as the starting point.

1. Delete the nomination discussion before adding the person to the GitHub org
   and maintainers team, so that it won't be visible to the new maintainer.

   _We hope this setup will enable honest and open discussions about both
   positive and negative things, preventing self-censorship we might apply if we
   knew the nominee was going to read it after joining the project. Having said
   that, our code of conduct applies to nomination discussions too. Keep your
   feedback civilized and constructive, as always._

1. Ask one of the team admins (@dhmlau, @raymondfeng) to invite the new
   maintainer to the team.

   Please note the new maintainer has to accept the invite via GitHub UI,
   consider to remind them e.g. via a Slack direct message.

