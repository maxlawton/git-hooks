Git Hooks
=========

To use these scripts, place them in the `.git/hooks` directory of your
repository. You may prefer to add it to your global git templates and
use `git init` instead. Run `git help init` and `git help hooks` for
instructions.

If you do not already have a git templates directory, you may wish to
create one and clone this repository as `hooks` within.


1. Prepare Commit Message
-------------------------

See [prepare-commit-msg](prepare-commit-msg).

This hook prepends commit messages with a numerical tag when
committing under numbered branches.

For example:

* `feature/8932-callout-links` -> "[#8932] ..."
* `ticket-39451` -> "[#39451] ..."

