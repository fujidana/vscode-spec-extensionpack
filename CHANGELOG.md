# Change Log

Previously the language identifier of this extension pack, `vscode-spec`, was used by an independent extension that supports both __spec__ command files and __spec__ log files.
Later, for several reasons the developer decided to split this extension into two; one is for __spec__ command files (both the exention identifier and language identifier are `spec-command`) and the other is for __spec__ log files (`spec-log`).

Check [CHANGELOG of the "__spec__ command"](https://github.com/fujidana/vscode-spec-command/blob/master/CHANGELOG.md) for the history when the `vscode-spec` was an independent extension.

The last version of the independent extension was v1.4.0.
Because the version number smaller than the previously published one is not allowed in the market place, this extension pack starts its version number from v2.0.0.

## [Unreleased]

## [2.0.1] - 2021-07-08

### Fixed

- wrong GitHub repository links

## [2.0.0] - 2021-07-01

### Added

- Initial release, which bundles
  - __spec command__ (`fujidana/spec-command`): language support for __spec__ command files
  - __spec log__ (`fujidana/spec-log`): language support for __spec__ log files

[Unreleased]: https://github.com/fujidana/vscode-spec-extensionpack/compare/v2.0.1...HEAD
[2.0.1]: https://github.com/fujidana/vscode-spec-extensionpack/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/fujidana/vscode-spec-extensionpack/releases/tag/v2.0.0
