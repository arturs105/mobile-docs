# Quality Control

The Toggl mobile team takes the quality of their products very seriously.

To ensure this quality is maintained, everyone on the team is responsible to test and review the app as part of their regular work.

Specifically:


## Developers

Developers are responsible to test all changes they make to the app, to make sure the app performs as intended. The same applies to reviewing pull requests: Both the submitter and the reviewers are responsible for ensuring that pull requests are only merged if they do not introduce bugs, glitches or other unintended behaviour.

### Tests

To make the developer's job easier (but not to remove responsibility), we aim for maximal (read: full) test coverage. Our goal is to have all functionality of the app **unit tested** and **ui tested**, to detect issues as quickly as possible.


## Product lead

The product lead is responsible for ensuring that the app is fully tested before release and performs as intended.

To enable this, developers may not release a new build without first informing the lead, and letting them test the app. Such a notice should always include a comprehensive change log compared to the previously tested build.

Further, once a build gets released, both the mobile team and the support team should be notified and given the change log of that release compared to the last.

For more information on the proper release flow, check the [SuperFlow documentation](https://github.com/toggl/mobile-docs/blob/develop/superflow.md#release-workflow "SuperFlow - Release workflow").