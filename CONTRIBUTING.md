# Contributing to CRESCENT

Thanks for your interest in the Cascadia Region Earthquake Science Center (CRESCENT) repositories. This guide applies to every repository in the `cascadiaquakes` organization unless a repository has its own `CONTRIBUTING.md`.

## Questions and bug reports

Open an issue in the repository the question or bug is about. Please include:

- A link to the page or file, if there is one
- What you did, what you expected, and what happened instead
- A screenshot or error message, if you have one

For general questions, email [cascadiaquakes@uoregon.edu](mailto:cascadiaquakes@uoregon.edu).

To report a security problem, do not open a public issue. See [SECURITY.md](SECURITY.md).

## Contributing data

Each CRESCENT data product has its own submission instructions:

| Data | Instructions |
|---|---|
| Earthquake catalogs | [Earthquake Catalog Repository](https://cascadiaquakes.github.io/earthquake_catalog_repository/submission/) |
| Velocity models | [CVM book](https://cascadiaquakes.github.io/cvm-tools-book/submission/) |
| Paleoseismology compilations | [CPAL book](https://cascadiaquakes.github.io/cpal-book/submission/) |
| Landslide inventories | [Ground Failure book](https://cascadiaquakes.github.io/cascadia-landslide-book/submission_instructions.html) |
| Faults | [CFM inclusion criteria](https://cascadiaquakes.github.io/cfm-book/inclusion-criteria/), then open an issue on [CRESCENT-CFM](https://github.com/cascadiaquakes/CRESCENT-CFM/issues) |

## Contributing code

1. Work on a branch, not directly on the default branch.
2. Open a pull request. Keep each pull request to one change, with a short commit message that says what it does.
3. CI must pass, and a maintainer reviews the pull request before it is merged.
4. Some repositories deploy to a dev environment automatically when a pull request is merged. Production deploys run separately and need a maintainer's approval.

## Standards

- **READMEs** follow the [README standard](README_STANDARD.md).
- **Licenses:** code is licensed under BSD-3-Clause and data under CC-BY-4.0, unless a repository says otherwise.
- **Releases and citation:** when a product is released, its `CITATION.cff` and Zenodo DOI are updated as described in [Releasing a new version](README_STANDARD.md#releasing-a-new-version).

## Contact

[cascadiaquakes@uoregon.edu](mailto:cascadiaquakes@uoregon.edu)
