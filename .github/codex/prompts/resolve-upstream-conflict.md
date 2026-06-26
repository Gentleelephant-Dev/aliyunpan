You are resolving an upstream merge conflict for a fork customization branch.

Use the current working tree and the provided GitHub context as the source of truth. A merge from upstream has already been attempted. Conflict markers may exist.

Project policy:
- This repository is a fork of an upstream project.
- The target branch contains local customizations.
- Preserve local customizations unless upstream clearly supersedes them.
- Never push directly to the target branch.
- Work only on the current temporary PR branch.
- Do not expose secrets.
- Prefer small, reviewable changes.

Task requirements:
- Resolve only existing merge conflicts.
- Prefer minimal, idiomatic changes over refactors.
- Do not rewrite unrelated files.
- Do not update generated files unless the repository workflow requires it.
- Run the smallest relevant checks available for touched files.
- If full checks are too expensive or dependencies are unavailable, say exactly what was and was not run.
- Leave the repository with no unmerged files.

Final response:
- Summarize conflicts resolved.
- List the most important changed files.
- Report checks run and results.
- Call out remaining risks or review points.
