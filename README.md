# Sample repository

This is a sample repository to demostrate some basic github features.

## How to clone a repo in git

To clone a repo in git, all you have to do is run `git clone <repo url>` in your terminal.

## How to push codes.
- run `git add .` (or `git add <file name>`)
- run `git commit -m <"your comment">`
- run `git push`

## How to associate a commit to an issue

> Source: [https://docs.devart.com/studio-for-sql-server/source-controlling-databases/associating-commits-with-github-issues.html](https://docs.devart.com/studio-for-sql-server/source-controlling-databases/associating-commits-with-github-issues.html)

To link a commit to a GitHub Issue, put the issue number with the # character in the Comment text box. For example, `#111`. To close a GitHub issue, put a keyword and put the issue number with the # character in the Comment text box. For example, Close `#111`.

### Keywords to close a GitHub Issue
To close a GitHub issue, you can use any of the following keywords:
- close
- closes
- closed
- fix
- fixes
- fixed
- resolve
- resolves
- resolved
> An example commit could be: *Made update to `fix #111`*.
