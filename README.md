# A Template Repository for Space Cubics

This repository serves as a template for Space Cubics. You can use it
when creating a new repository. You can add, remove, or modify the
settings to fit your project.

## Codespell

https://github.com/codespell-project/codespell

Codespell is a tool for fixing common misspellings in text files. You
can add project-specific words to `.codespell-ignore` so that
codespell will ignore them.

## gitlint

https://github.com/jorisroovers/gitlint

gitlint is a linter for git commit messages. In our configuration,
gitlint checks all commits in a given pull request.

Special care is taken for lines that start with common Signed-off-by
lines or HTTPS references. See `.gitlint` for more details.

## linelint

https://github.com/fernandrone/linelint

linelint is a linter that checks for a trailing newline at the end of
a file. In C, a source file without a final newline is not valid.
This may not suit every repository or programming language, so remove
it if you do not need it.

## .gitignore

`.gitignore` specifies intentionally untracked files that Git should
ignore. The contents of this file may vary from project to project,
but you probably already know what to put here.

## .editorconfig

`.editorconfig` defines basic coding style settings for the project.
Many editors, such as Emacs, Vim, and Visual Studio Code, support it.
