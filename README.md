# CV Workshop -- Day 2

![Git Branching Diagram](https://git-scm.com/book/en/v2/images/lr-branches-1.png)

## Lab Tasks
- Created branches: dev, test
- Merged to main
- Created tag v1.7

To delete branches locally:

git branch -d dev      # Delete dev branch locally
git branch -d test     # Delete test branch locally

To delete branches remotely:

git push origin --delete dev
git push origin --delete test

To checkout another branch without committing changes:

git stash              # Save uncommitted changes
git checkout other-branch
git stash pop          # Restore changes in new branch


To delete tag locally:
git push origin --delete v1.7

To delete tag remotely:
git push origin --delete v1.7





