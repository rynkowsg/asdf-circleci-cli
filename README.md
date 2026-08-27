<div align="center">

# asdf-circleci-cli
[![GitHub Actions Test Status][ci-actions-test-badge]][ci-actions-test]
[![GitHub Actions Lint Status][ci-actions-lint-badge]][ci-actions-lint]
[![CircleCI Lint Status][ci-circleci-lint-badge]][ci-circleci-lint]
[![License][license-badge]][license]

[ASDF][asdf-website] plugin for [circleci-cli][circleci-cli-repo].

</div>

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Supported versions](#supported-versions)
- [License](#license)

## Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

## Install

Install the plugin:

```shell
asdf plugin add circleci-cli https://github.com/rynkowsg/asdf-circleci-cli.git
```

Install circleci-cli:

```shell
# Show all installable versions
asdf list-all circleci-cli

# Install specific version
asdf install circleci-cli 0.1.38646

# Set a version globally (on your ~/.tool-versions file)
asdf global circleci-cli 0.1.38646

# Now circleci tool is available
circleci --help
```

Check [asdf][asdf-repo] readme for more instructions on how to install & manage versions.

## Supported versions

The plugin installs any released version. A number of tags upstream never got a
release; `asdf list-all` leaves those out, since there would be nothing to
download for them.

## License

See [LICENSE](LICENSE) © [Grzegorz Rynkowski][gh-profile-rynkowsg]

[asdf-repo]: https://github.com/asdf-vm/asdf
[asdf-website]: https://asdf-vm.com
[ci-actions-lint-badge]: https://github.com/rynkowsg/asdf-circleci-cli/actions/workflows/lint.yml/badge.svg
[ci-actions-lint]: https://github.com/rynkowsg/asdf-circleci-cli/actions/workflows/lint.yml
[ci-actions-test-badge]: https://github.com/rynkowsg/asdf-circleci-cli/actions/workflows/test.yml/badge.svg
[ci-actions-test]: https://github.com/rynkowsg/asdf-circleci-cli/actions/workflows/test.yml
[ci-circleci-lint-badge]: https://circleci.com/gh/rynkowsg/asdf-circleci-cli.svg?style=shield
[ci-circleci-lint]: https://circleci.com/gh/rynkowsg/asdf-circleci-cli
[circleci-cli-repo]: https://github.com/CircleCI-Public/circleci-cli
[gh-profile-rynkowsg]: https://github.com/rynkowsg
[license-badge]: https://img.shields.io/badge/license-MIT-lightgrey.svg
[license]: LICENSE
