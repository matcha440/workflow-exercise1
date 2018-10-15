# Demo of a GitHub App to enforce a workflow

[Work in Progress](https://probot.github.io/apps/wip/) sets a status using the GitHub API. This status can then be used to block a merge.

### See it in action

1. Fork this repository.
1. Make a change to the codebase.
1. Create a pull request against the upstream repository with _WIP_ in the title.
1. Remove _WIP_ from the title, merge isn't blocked :tada:.

### Install it yourself

1. Install [Work in Progress](https://probot.github.io/apps/wip/) by clicking "Add to GitHub"
1. Install it on your fork
1. Make a change to the codebase.
1. Create a pull request against your repository with _WIP_ in the title.
1. Navigate to repository Settings > Branches > Branch protection rules > Add rule
1. Select: Apply rule to `master`
1. Select: Require status checks to pass before merging
1. Select: WIP
1. Return to the PR, notice the merge is blocked. 
1. Remove _WIP_ from the title, merge isn't blocked :tada:.
1. Merge your PR. 
