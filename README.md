# git-branching-strategy
git-branching-strategy


1. For each pull request to be merged to the develop there should be 2 approvals one from developers and other from testers (check if i can add groups) because the merge triggers a release to the testing environment. and after the testing is done on that release we can add an approver and on his approval that release is published/deployed to the production with release tags.

2. Every feature or bugfix should be a implemented on a seperate branch dedicated to that.

3. Everyone should use prefixes namely : 'fix', 'hotfix' or 'feat' for identifying the merge so that the versioning can be implemented easily.
fix or hotfix: increase the patch
feat: increase the minor or major based on #message(messages: 'major' and 'minor').

minor change test.