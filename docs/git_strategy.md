# GIT guidelines

## Regular branches

### main
- contains only code that works

### feature branches
- branched from **main**
- naming convention `<branch type>-<brief description>-<task # opt>`
- use dashes (`-`) between name parts and underscore (`_`) with name parts
- branch type
    - **feature** - feature branch with planned release
    - **wip** - work in progress branch with no planned release
- description - short description of changes in branch
- task # - optional value used to tie back to a story

*Example*: `feature-update_branch_strategy_docs-1`

## Pull request
The pull request should have a descriptive title.  
It should describe the changes, any further action needed and if possible specify the testing.

*Example*
> # Update branch strategy in docs
> Add initial documentation for git strategy including branching and PR guidelines


After merging the branch to main, we should delete the branch unless we expect a small change in a short period of time.
