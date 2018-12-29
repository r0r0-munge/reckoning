# Contributing

## Fork and clone the repository
1. Fork this repository through the GitHub web UI while being logged in as yourself. Browse to the repository and click "Fork" in the top right. You will fork to your own GitHub account.  This allows you to work on changes locally and make sure that they're awesome before you submit to the project maintainer.
1. From your repository page in the GitHub web UI, click the "Clone or download" to copy the repo URL.
1. Go to your terminal window on your computer `git clone URL`
1. Cd to the new directory.  You have successfully forked the repository.

## Link to the remote repository
1. type `git status` to get the current git status.
1. Type `git remote -v` to see information about the remote repository
1. Browse to upstream URL (the place where you forked the repository from), click "Clone or download" to copy the repo URL.
1. Go back to terminal to set up stream using `git remote add upstream [URL]`
1. Synch with upstream using `git fetch upstream`

## Create and checkout your branch
1. Create branch to work on and checkout that branch. `git checkout -b [BRANCH_NAME]`
1. To work on a branch that already exists on the remote, use `git checkout [BRANCH_NAME]`
1. Now make all your changes. They are tracked with your branch name.

## Commit and push your changes
1. Add your changes by `git add -A`
1. Commit your changes by `git commit -m "NOTE_DESCRIBING_CHANGE"` Make sure that your change is only one thing, in one area of the code.
1. Push your changes to your your fork in your repository `git push --set-upstream origin [BRANCH]``
1. Now, create the pull request in the browser UI to send to the remote repository maintainer
