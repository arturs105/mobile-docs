# Pull Request Etiquette

**Our goal as the mobile developers at Toggl is to create apps of the highest quality in terms of both the user experience and the code base.**

All code changes to our apps are added using GitHub's pull requests. To be able to merge a pull request, it has pass unit tests and be approved by at least one other developer. Therefore it is of supreme importance that each pull request is as easy to review as possible. To facilitate this, follow these guidelines:

1. Pull requests should always result in a functional app and never knowingly introduce bugs or other bad behaviour
2. Pull requests should be as small and straight forward as possible
    - Each pull request should make a single clearly defined change or addition
    - Change as many files as necessary, but as few as possible
    - Do not add unrelated changes - even minor code cleanup - to your pull request
        - Create a separate pull request instead
        - If possible, split larger pull requests into multiple ones
3. Pull requests should be presented well
    - Use a clear and succinct title
        - If this is not possible, the pull request is most likely too big
    - Add a description if the changes are not trivial
        - Rather add too much detail, than too little
    - Add references to related issues/pull requests to the description
        - If the pull request closes an issue, [include `Closes #issue`](https://github.com/blog/1506-closing-issues-via-pull-requests)

It is the contributor's responsibility to make sure the merging branch is up to date with the base branch. If you would like feedback on a work-in-progress feature, feel free to create a pull request and mark it with the `wip` label. Make sure to comment on what kind of feedback you are looking for.

## Code review

Code review is one of the primary ways we ensure the quality of the apps. **Code can only be merged into the main branches of the repository if it has been read, understood, analysed, and accepted as correct by at least one other developer.** For larger features feedback from multiple developers might be needed to ensure correctness.

In principle anyone can review any pull request, if they feel confident to do so. Optionally, the author of the pull request, the tech lead, or existing reviewers may request for reviews from specific people, based on their familiarity of experience with the affected systems.

If more than one review is requested, the pull request may only be merged if all reviewers have accepted it.

Developers should be thorough and critical with both their own code, but especially when reviewing. Requested changes should only be implemented if the contributor agrees with them. Otherwise the change should be discussed.

A pull request should only be accepted after a full review and if the reviewer is confident of the code's correctness and conformity to our guidelines.

After a pull request has been approved it should not be changed except for bringing it up to date with the base branch, assuming the merge does not call into question the correctness of the pull request. Any other changes have to be explicitly agreed upon by reviewers though it is highly preferable to only accept the pull request once it is complete and up to date.

## Merging pull requests

Once a pull request is up to date with the base branch and approved, it should only be merged by the original contributor, unless they explicitly state that a reviewer is allowed to merge.

When merging, consider which type of merge supported by GitHub is the best choice. Most pull requests should be small enough to be squashed into a single commit that still follows the commit guidelines. If this can not be done, prefer merging over rebasing to keep history intact.
