# Pull request process

The pull request (PR) process reflects the team culture on collaborating within
the open source project. At LoopBack, we strive to foster a supportive,
collaborative, and constructive environment for everybody to enjoy working
together with the same passion to create great values for our community. Both
community and code matter for us.

Our maintainers are very distributed around the world with different time zones
and work schedules. Some of us are paid full-time IBM employees while others are
voluntary community contributors. Most of our changes are officially accepted
into the code base via pull requests.

To facilitate collaborations, this document establishes a protocol on reviewing,
approving, and landing a pull request for [loopback-next](https://github.com/strongloop/loopback-next).
It has the following objectives:

1. Defines a process that PR author and reviewers can follow
2. Set the expectations among our maintainers who are distributed
3. Strike a good balance between the time we can land a PR and the quality of
   the proposed change

For general knowledge about github PR process, see:

https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/proposing-changes-to-your-work-with-pull-requests

We also have a tutorial to cover how to submit a PR to `loopback-next`:

https://loopback.io/doc/en/lb4/submitting_a_pr.html

## The PR process

### Submit a PR

Provide some context

- Pointing to an existing issue
- Summarizing the problem/solution
- Linking to document changes/diagrams

Check the items from the PR template

Set the right labels

Consider to break complex PRs into a few smaller ones

### Assign a primary owner and nominate additional reviewers

When a PR is submitted, github automatically suggest some of reviewers based on
(CODEOWNERS)[https://github.com/strongloop/loopback-next/blob/master/CODEOWNERS]
and those who have worked on the code recently.

### Review a PR

The reviewers should make it explicit for different categories of feedbacks, such as:

- Must have/fix (the author must address such comments)
- Nice to have/fix (the author should try to address such comments but they don't
  block the PR from being landed)
- Nitpick (up to the author to decide)

For `Must have/fix` Request changes

Ping peers if the process is stalled.

- https://google.github.io/eng-practices/review/reviewer/
- https://blog.pragmaticengineer.com/good-code-reviews-better-code-reviews/
- https://medium.com/palantir/code-review-best-practices-19e02780015f

Iterative commits

To address review comments, it's recommended to keep pushing new commits as the
PR will automatically pick up new changes pushed to the same source branch.

Such commits should be squashed and reorganized to maintain a clean history.

### Approve a PR

### Veto a PR

### Land a PR

Minimum requirements:

- CI is green (with exceptions that the failure is caused by known issues)
- Approved by the owner
- Approved by mandatory reviewers

If the author of a PR is a maintainer, he/she will be responsible for landing
the PR upon approvals. Otherwise, the owner of the PR should land it on behalf
of the community contributor.

Other maintainers can land the PR for the author too to avoid further delays
in case of preparing a release or fixing build breaks.

Depending on the nature of a PR, we'll decide the minimum duration that we keep
it open even if the minimum criteria have been met so that other maintainers will
have a chance to review the changes.

- Trivial changes, such as fixing typos, code formatting issues, eslint violations

### Follow up a PR

- Additional reviews/comments
- Create follow-up stories
- Submit follow-up PRs
- Revert a PR
