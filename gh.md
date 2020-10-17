# GitHub CLI
Released 2020/09/16
Documentation: https://cli.github.com
Project repository: https://github.com/cli/cli

Interactive login to GitHub: `gh auth login`

Logout: `gh auth logout`

Create a new repo on GitHub from a local repo: `gh repo create`

Simplified syntax for cloning a repo: `gh repo clone <owner>/<repo>` = `git clone https://github.com/<owner>/<repo>.git`

Create a PR: gh pr `create -B master -b "This is a PR to test gh" -t "TEST PR"`

PR diff: `gh pr diff --color auto`

List PRs `gh pr list` - has multiple filters

Close, reopen PR `gh pr close`, `gh pr reopen`

Review a PR: `gh pr review`

Show PR in browser `gh pr view <pr-id> -w`

Creating and maintaining issues: `gh issue`

Creating and maintaining releases: `gh release`

Sending a GitHub API request: `gh api`



