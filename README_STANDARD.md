# CRESCENT README Standard

Every public repository in the `cascadiaquakes` organization uses the same README layout, so visitors can find the same information in the same place in every repo.

## Top of every README

```markdown
# Repository Title

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)
[![License: BSD-3-Clause](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](LICENSE)

One paragraph on what this repository is.

**Live viewer:** https://...

**Documentation:** https://...
```

Include the DOI badge only if the repo has a Zenodo DOI. Keep a blank line between link lines, or GitHub renders them as one line.

## Sections by repository type

Pick the column that matches the repository and use its sections in this order. Sections in *italics* are included only when they apply.

| Products (viewers and services) | Books | Data and tools | Workshops and courses |
|---|---|---|---|
| Documentation | Contents | *Repo's own content sections* | *Course sections* |
| Features | Building Locally | License | Instructors |
| Data | Deployment | Contacts | License |
| *Technology Stack / Architecture* | *Contributing* | Acknowledgments | Acknowledgments |
| Running Locally | *How to Cite* | | |
| Project Structure | License | | |
| *API / Database Schema* | Contacts | | |
| Deployment | Acknowledgments | | |
| *Troubleshooting / Performance* | | | |
| How to Cite | | | |
| License | | | |
| Contacts | | | |
| Acknowledgments | | | |
| *Disclaimers* | | | |

Long maintainer-only material (admin setup, teardown steps, internal to-do lists) goes in `docs/MAINTAINERS.md`, linked from Deployment, rather than in the README.

## Acknowledgments block

```html
<table>
  <tr>
    <td align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/cascadiaquakes/.github/main/assets/crescent-circle.png" alt="CRESCENT Logo" width="150" />
    </td>
    <td align="center" valign="middle">
      <img src="https://raw.githubusercontent.com/cascadiaquakes/.github/main/assets/nsf-logo.png" alt="NSF Logo" width="450" />
    </td>
  </tr>
</table>

This project is supported by the National Science Foundation through the Cascadia Region Earthquake Science Center (CRESCENT), Cooperative Agreement EAR-2225286.
```

## Examples

- Product: [cascadia-earthquake-viewer](https://github.com/cascadiaquakes/cascadia-earthquake-viewer)
- Book: [cfm-book](https://github.com/cascadiaquakes/cfm-book)
- Data: [CRESCENT-CFM](https://github.com/cascadiaquakes/CRESCENT-CFM)
- Workshop: [2026_Geodesy_TSC](https://github.com/cascadiaquakes/2026_Geodesy_TSC)
