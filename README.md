# Repository Title

Brief description.

# TO DO

* Edit the LICENSE file to include the current year and the copyright holder's full name (typically that of the owner of a new repository).

* Edit `.github/workflows/release.yaml` and replace `...` with the name of your executable

**Don't forget to delete this section of the README!**

## Pull Requests

Pull requests are welcome. Please ensure they conform to the conventions described below.

## Releasing

To build and release this repository, push a tag of the form
`vn.n.n`. A github action will attempt to cross-compile
binaries from the Rust source and store them in the release
on github.

### Conventions

The `.editorconfig` file captures basic source files formatting conventions.
Many editors support this file natively; others (such as VS code) require a plugin, see https://editorconfig.org/.

The default branch is `main`. See [Renaming the default branch from master](https://github.com/github/renaming) for the rationale.

Commit logs should describe the specific changes made by a commit. See [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/).
