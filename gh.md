# GitHub CLI
Released 2020/09/16
Documentation: https://cli.github.com
Project repository: https://github.com/cli/cli

Interactive login to GitHub: `gh auth login`

Logout: `gh auth logout`

Create a new repo on GitHub from a local repo: `gh repo create`

Show repo in browser: `gh repo view -w`

Simplified syntax for cloning a repo: `gh repo clone <owner>/<repo>` = `git clone https://github.com/<owner>/<repo>.git`

Create a PR: gh pr `create -B master -b "This is a PR to test gh" -t "TEST PR"`

PR diff: `gh pr diff <pr-id>`

List PRs `gh pr list` - has multiple filters

Close, reopen PR `gh pr close <pr-id>`, `gh pr reopen <pr-id>`

Review a PR: `gh pr review <pr-id>`

Show PR in browser `gh pr view <pr-id> -w`

Merge PR: `gh pr merge <pr-id>`

Creating and maintaining issues: `gh issue`

Creating and maintaining releases: `gh release`

Sending a GitHub API request: `gh api`



