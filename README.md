# gill-contribution [project link](https://github.com/users/hnariman/projects/11)

## ideas on contribution:
(this is an open document, please feel free to improve/extend it to help peers get rolling with their contributions asap)

### where to start:
#### Setup:
- fork the repository to your github [guide](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)
- make sure you're update with current origin (original repo), if necessary do git pull etc
- as gill is an sdk to be used on project, highly advice getting some project scaffold in parallel (using something like ```npx create-solana-dapp```)
- create a branch with feature name or issue, best practice is to use [conventional names](https://conventional-branch.github.io/)
- to use local version of sdk in the scaffold project use ```npm link``` or ```pnpm link```
- do the changes in sdk, build sdk, make sure changes are working in the scaffold project, if yes, you're possibly good to go with sdk development

#### before contribution to origin
- make sure project builds (don't push broken changes)
- make sure all tests are passing (don't push broken changes)
- make sure your commits are clean/clear, no console.logs or extra junk is left
- make sure to push your commits to your own git repo first, then open a PR to origin, check the docs [guthub docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork), if not sure ping peers in dicsord and ask for help, there are no stupid questions, contribution is a team work, answering questions is also a learning activity, so don't be shy
(it's always better to ask now and look confused for 5 minutes, rather than to never ask and remain confused for days)

> doing this intro in a hurry, it's rough guideline, hopefully will update with more info soon

### Resourses:
[about git branches](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
[npm link usage example](https://dev.to/brunosartori/mastering-npm-link-simplifying-local-dependency-management-ggo)
[pnpm link documentation](https://pnpm.io/cli/link)
