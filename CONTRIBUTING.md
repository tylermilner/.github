> ⚠️ **UPDATES REQUIRED** ⚠️
> 
> Make sure to update the content in this guide as necessary:
> - Update `repo_name_here` placeholder in repo `[fork]` and `[pr]` URLs at the top of this file
> - Verify `LICENSE` and `CODE_OF_CONDUCT.md` files exist and the URLs here are valid
> - Complete the **TODO**'s below as necessary
> - Remove these notes once complete

# Contributing

[fork]: https://github.com/tylermilner/repo_name_here/fork
[pr]: https://github.com/tylermilner/repo_name_here/compare
[code-of-conduct]: CODE_OF_CONDUCT.md

Hi there! We're thrilled that you'd like to contribute to this project. Your
help is essential for keeping it great.

Contributions to this project are
[released](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license)
to the public under the [project's open source license](LICENSE).

Please note that this project is released with a
[Contributor Code of Conduct](code-of-conduct). By participating in this project
you agree to abide by its terms.

## Source Code Overview

[ ] **TODO**: A high-level overview of the main files involved in the project

## Making Code Changes

[ ] **TODO**: The steps necessary to get the project up-and-running on a developer's local environment

## Submitting a pull request

[ ] **TODO**: Update `insert_command_here` placeholders in below steps to install dependencies, run tests, etc.

1. [Fork][fork] and clone the repository
2. Configure and install the dependencies: `insert_command_here`
3. Make sure the tests pass on your machine: `insert_command_here`
4. Create a new branch: `git checkout -b my-branch-name`
5. Make your change, add tests, and make sure the tests still pass
6. Do one final check to ensure all tests, linter, and compilation steps pass:
   `insert_command_here`
7. Push to your fork and [submit a pull request][pr]
8. Pat your self on the back and wait for your pull request to be reviewed and
   merged.

Here are a few things you can do that will increase the likelihood of your pull
request being accepted:

- Follow the style guide style by running the linter `insert_command_here`.
- Write tests.
- Keep your change as focused as possible. If there are multiple changes you
  would like to make that are not dependent upon each other, consider submitting
  them as separate pull requests.
- Write a
  [good commit message](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).

## Creating a Release

When it comes time to create a new release, repository maintainers should follow
the steps below to create and publish a new release.

### Versioning

For versioning, we are following [semantic versioning](https://semver.org).

### Automated Release

[ ] **TODO**: Add automated release instructions

### Manual Release

Perform the following steps to create a manual release:

1. Make sure all desired changes have been pushed to the `main` branch.
2. Create a `release/*` branch off of `main` (e.g. `release/v1.0.1`).
3. Update the version in any necessary manifest files (e.g. `package.json` to the desired version.
4. Create a pull request from the `release/*` branch to `main`.
5. Once the pull request is merged, create a new release targeted on `main` in
   the GitHub UI. Make sure to set it to create the corresponding tag on publish
   (e.g. `v1.0.1`) and keep the "Publish this Action to the GitHub Marketplace"
   option checked.

## Resources

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)
