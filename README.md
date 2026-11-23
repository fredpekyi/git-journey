# git-journey

A practice repository for learning everyday Git and GitHub workflows. The files
(`one.txt`, `two.txt`, `three.txt`, `four.txt`, `myFolder/`) hold simple placeholder
content. What matters is the history, which shows each Git concept in action.

## Git concepts practised

| Concept | Where to see it |
| --- | --- |
| Creating a repo and committing files | Initial commits creating `one.txt` and `two.txt` on GitHub |
| Staging and committing changes locally | Commits adding lines to `one.txt`, `two.txt` and `three.txt` |
| Working with folders | `myFolder/three.txt` |
| Branching | `main`, `development`, `staging` and `feature` branches |
| Merging branches | "Merge main into development" |
| Resolving a merge conflict | Conflicting edits to line 2 of `two.txt` (`22` vs `222`), resolved in favour of `222` |
| Pushing and pulling with a remote | `origin` on GitHub, with edits made both locally and in the GitHub web editor |
| Undoing a commit with `git revert` | "Add "Another feature" line to one.txt" followed by its revert |
| Feature-branch workflow | Dark mode work (`four.txt`, `one.txt`) on the `feature` branch |
| Configuring identity | `git config --global user.name` / `user.email` matched to the GitHub account |
| Writing clear commit messages | Short, imperative messages that say what changed |

## Branches

- `main`: the stable branch
- `development`: integration branch, where the merge and conflict practice took place
- `staging`: mirrors `development`, for practising promotion between environments
- `feature`: dark mode work in progress
