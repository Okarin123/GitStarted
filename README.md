# GitStarted
Getting started with Git. Check out the CheatSheets and Guides - they're valuable reference material.
## Topics
- [x] What is Git?
- [x] What is GitHub?
- [x] git add, tracked and untracked files
- [x] git status
- [x] git diff 
- [x] git commit
- [x] git remote
- [x] git push
- [ ] git pull
- [ ] git clone
- [ ] README and Markdown
- [ ] What are forks?
- [ ] What are branches?
- [ ] git branch, git checkout
- [ ] What is a PR?
- [ ] Merging and merge conflicts
- [ ] Open Source Contributions
- [ ] GitHub Pro (Student Pack)
- [ ] Your own website!
## What do you have to do?
We'll be learning some important concepts using this repository. Follow the instructions below.
1. Fork this repository - this creates your-username/GitStarted, which is like your copy of this repository. Forks are not automatically updated. To fork, press the `Fork` button at the top.
2. Create a local clone of the repository. This means you download the repository onto your system, to have a local clone or copy of it. You can make changes to the files here and later commit and push these changes. Use `git clone https://github.com/your-username/GitStarted.git`.
3. Check `git remote`, and you should see `origin`. This remote points to your fork of this GitHub repository. Now, add a remote pointing to this repository, called `upstream` using `git remote add upstream https://github.com/ssncsegithub/GitStarted`.
4. Pull any changes made to this repository using `git pull upstream master`, to synchronize your local and retrieve any new changes made.
5. Checkout to a new branch using `git checkout -b new-branch-name`. This is done so that your experimental changes are kept separate from `master` which is stable.
6. Add your name to the `Names.md` file in Markdown syntax, and link to your GitHub profile. Make these changes locally.
7. Once you're happy, commit and push these changes. You will be pushing the changes to your GitHub repostory's branch using `git push origin new-branch-name`.
8. Go to your fork on GitHub and click `New Pull Request`. Edit the details and submit the PR.
9. Wait for it to be merged. Once merged, delete your new branch on GitHub (this can be done from the PR using a shortcut). Locally, checkout to `master` and use `git branch -D new-branch-name`.
10. Pull changes fom `upstream`, push to `origin master`.
