# doiderao-labs defaults

Default community health files for every repo in this org, per GitHub's
[default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) rules.

`ISSUE_TEMPLATE/` holds the fleet's two issue templates:

- `backlog.md` — a raw idea, definition only.
- `refinement.md` — a spec ready to build, written with worktree-repos' `/interview`.

`PULL_REQUEST_TEMPLATE.md` is the fleet's PR body: What with the `Closes #N`
line, Evidence, and Deviations only when the spec was not followed to the letter.
Agent-written PRs follow the same three sections (worktree-repos' `/code` skill).

Edit them here and every repo without its own `.github/ISSUE_TEMPLATE/` folder
picks the change up immediately. A repo that keeps its own folder overrides
these entirely, so the fleet repos carry none.

This repo is public because GitHub requires it for defaults; nothing here is secret.
