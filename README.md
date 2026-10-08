![ALMARFELD â€” practical Windows utilities](assets/banner.svg)

ALMARFELD is an independent software project by **Alin Radulescu (AlinTibi)**, focused on small, useful Windows utilities. The applications are free and open source, with local processing and straightforward portable distribution.

## Software

| Application | Workflow | Links |
| --- | --- | --- |
| **FolderWatch** | Save folder snapshots, compare changes and export filtered reports. | [Product](https://almarfeld.com/software/folderwatch/) Â· [Source](https://github.com/AlinTibi/FolderWatch) |
| **API Model Forge** | Turn JSON into C#, TypeScript, Kotlin, Python and Go models. | [Product](https://almarfeld.com/software/api-model-forge/) Â· [Source](https://github.com/AlinTibi/APIModelForge) |
| **MetaClean** | Inspect and remove supported file metadata using ExifTool. | [Product](https://almarfeld.com/software/metaclean/) Â· [Source](https://github.com/AlinTibi/MetaClean) |
| **Subtitle Doctor** | Inspect, repair, edit and synchronize subtitle files. | [Product](https://almarfeld.com/software/subtitle-doctor/) Â· [Source](https://github.com/AlinTibi/SubtitleDoctor) |
| **Config Doctor** | Inspect configurations, compare a baseline and diagnose .env references. | [Product](https://almarfeld.com/software/config-doctor/) Â· [Source](https://github.com/AlinTibi/ConfigDoctor) |
| **P7S Universal Viewer** | Open signed containers, inspect each signer and extract original content. Version 2.0.0 is released. | [Product](https://almarfeld.com/software/p7s-universal-viewer/) Â· [Source](https://github.com/AlinTibi/p7s-universal-viewer) |

## Distribution and safety

- Windows x64 portable releases, with CI builds/tests and SHA-256 checksum files.
- Current ALMARFELD release tags are signed; the preserved legacy P7S v1.0.0 tag predates this policy. Windows executables are **not Authenticode signed**; a signed tag does not replace checking the downloaded ZIP's checksum.
- Applications process files locally without accounts, analytics or uploads. Wails applications require Microsoft Edge WebView2 Runtime separately; MetaClean includes ExifTool in its portable package.
- P7S v2.0.0 uses .NET 10 / WPF and requires WebView2 only for PDF preview; certificate trust and integrity are separate, and revocation is not checked.
- Application source is MIT licensed. Dependencies retain their own licenses.
- MetaClean does not guarantee secure PDF sanitization or anonymization: PDF metadata writes may be incremental and reversible.

[Browse all software](https://almarfeld.com/software/) for screenshots, current releases, requirements and product-specific limitations.

## Contact

[almarfeld.com](https://almarfeld.com) Â· [contact@almarfeld.com](mailto:contact@almarfeld.com)

Software support: [support@almarfeld.com](mailto:support@almarfeld.com). Report reproducible bugs and feature requests in the application's issue tracker. Never attach private files or credentials.

Security reports: [security@almarfeld.com](mailto:security@almarfeld.com).
