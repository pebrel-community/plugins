# Pebrel Plugins

[中文](README.zh-CN.md)

The plugin directory for [Pebrel Community](https://github.com/pebrel-community).
Share plugin source, author attribution, versioned releases, and compatibility
information through pull requests.

This repository does not introduce
a new execution engine, permission model, or in-app plugin marketplace.
Current plugin capabilities are documented in the
[main project's plugin documentation](https://github.com/Kuddev/pebrel/tree/main/nebula_app/src/plugins).

## Listed works

| Work | Author | Category | Version |
| --- | --- | --- | --- |
| [pebrel-pi-wsl](entries/pebrel-pi-wsl.md) | [VauntlekV](https://github.com/VauntlekV) | Pi / WSL integration | 0.1.0 |

Compatibility evidence and review scope are attached to each work. An integration
may be installed in an external tool rather than Pebrel's own plugin runtime.

## Share a plugin

Show your work in [Show and tell](https://github.com/pebrel-community/plugins/discussions/categories/show-and-tell),
or open a [plugin submission](https://github.com/pebrel-community/plugins/issues/new?template=share-plugin.yml).

Keep the source and releases in your own repository. A directory submission
must identify the name, author, source, license, version, entry point, required
host capabilities, and actually tested Pebrel versions and platforms.

The initial catalog records `kind` and `runtime` separately. Integration entries
document their actual external installation path; they are not relabeled as
native Pebrel packages. Future automated installation must validate the appropriate
runtime contract and pinned artifact. Listing metadata alone does not enable it.

Works retain their own licenses. Shared contribution guidance lives in the
[organization's defaults repository](https://github.com/pebrel-community/.github/blob/main/CONTRIBUTING.md).
Directory documentation is MIT licensed.
