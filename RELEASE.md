# Release Notes for PyShell

**0.1.0:**
- Initial pass at `base` module.
- Direct inclusion of `config` module.
- Initial pass at `BackUp` script.
- Poor pass at `PyPackage` script.
- Simple (and incomplete) documentation.

**0.2.0**
- Backup Engine rewrite.
- Configuration improvements
- CLIEngine has before\_configure and after\_configure methods.

**0.3.0**
- Improved Examples and Documentation.
- Better Core-Module Features.
- Customizability of the configuration arguments.
- Improved configuration merges.
- Inverse Merge abilities.
- Configuration.make() classmethod.
- Support for multiple YAML files in configurations through callbacks.
- New `loggers` module to support colored and customized log messages.
- Pipeline improvements.
- Subcommand bug fixes.
- Improved utility functions.
- Expanded tests.

**0.3.1**
- Fixes to the internal structure in `config` module.
- Documentation improvements.

**0.3.2**
- Fixes for the internal structure in `config` module. Specifically, delete, set and contains.
- Tweaks to warning logs.

**0.4.0**
- Postmortem Plugin for nosetests
- Travis-CI support & better support for ``python3``.

**0.4.1**
- `flatten` and `expand` for nested configurations.
- `BumpVersion` script for bumping file versions

**0.5.0**
- `BumpVersion`
- Improvements to `BackUp` script

**0.6.0**
- Descriptors everywhere!
- `yaml` subpackage
- `astron` subpackage
- `config` subpackage with descriptors and argparse actions
