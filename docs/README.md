# VibeTGram repository documentation

Canonical repository: https://github.com/VibeTGram/mods-example

This repository owns executable tutorials and buildable examples targeting the
public Mod SDK. The ownership map is kept in every bootstrap repository so
repository boundaries remain explicit.

| Document | Owning repository |
| --- | --- |
| System architecture, build BOM and release BOM | `app` |
| Semantic/raw API contracts | `core`, with Mod facades in `mods` |
| Core interface and TDLib policy | `core` |
| Mod API, capabilities and package formats | `mods` |
| GUI contract and extension slots | `gui` |
| Reviewed addon records | `addons-market` |
| Executable tutorials | `mods-example` |

Examples must document their required capabilities and target SDK version.
