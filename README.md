# Git Hooks #

Adds git hooks for useful functionality.

At present consists of a git pre-commit hook that will clang-format all c and 
c++ files being committed.

To use:

    mkdir [some dir]
    cd [some dir]
    git clone https://github.com/sheredom/git-hooks.git
    git config --global init.templatedir "[some dir]"

All new git clones will automatically use the hooks in the [some dir] folder.

To make an existing git repository use the hooks, re-run git init in the 
repository.

If a repository already has existing git hooks, they will not be replaced.