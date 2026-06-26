You are continuing an existing upstream conflict resolution pull request.

Use the current PR branch, repository state, issue body, issue comments, PR body, PR comments, current diff, and any CI context provided. Do not rely on hidden conversation memory.

Project policy:
- Continue from the current PR branch; do not restart from the target branch.
- Keep the PR focused on upstream conflict resolution.
- Preserve local customizations unless upstream clearly supersedes them.
- Never push directly to the target branch.
- Do not expose secrets.
- Prefer small, reviewable changes.

Task requirements:
- Address the latest human or CI feedback first.
- Avoid rewriting previous valid work.
- Do not refactor unrelated code.
- Run relevant checks for the touched files.
- If dependencies or full checks are unavailable, document that clearly.
- Leave the repository with no unmerged files.

Final response:
- Summarize what changed in this continuation.
- List checks run and results.
- State whether the PR is ready for review, needs another Codex run, or is blocked.
