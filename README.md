# CV Workshop -- Day 2

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




