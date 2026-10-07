# Internationalization Intelligence Platform

## Overview

This repository contains the static HTML interface for the **Internationalization Intelligence Platform**, an internal dashboard for reviewing internationalisation data across institutions, partners, departments, and units.

The platform supports analysis of partnership agreements, collaboration activities, research outputs, student exchange, and annual departmental reports. It also provides follow-up views for active agreements that do not yet have linked research outputs, activities, or student-exchange records.

## Key Features

| Area | Description |
|---|---|
| Selection Panel | Filter information by region, country, ranking, institution, partner, or unit. |
| Overview | Review headline totals, trends, maps, and partnership-agreement follow-up indicators. |
| Partnership Agreements | Examine agreement types, validity, activity status, partner information, and contacts. |
| Activities | Review collaboration activities by year, department, agreement type, and activity type. |
| Research Outputs | Analyse scholarly output, citations, Avg FWCI, subjects, and researcher contributions. |
| Year Report | Review annual activities, research outputs, student exchange, and partner-institution figures for a selected department or unit. |
| Follow-up Alerts | Identify active agreements without recorded outputs, activities, or student exchange, then send an email alert to the responsible colleague or department. |

## Repository Structure

```text
.
├── static/
│   ├── EdUHK_Logo_RGB.png
│   ├── OIDR-logo-color.png
│   ├── back_arrow.png
│   └── favicon.png
├── templates/
│   └── internationalization_the.html
└── README.md
```

| Path | Purpose |
|---|---|
| `templates/internationalization_the.html` | Main HTML file for the Internationalization Intelligence Platform interface. |
| `static/` | Static visual assets used by the interface, including institutional logos, icons, and the favicon. |
| `README.md` | Project overview, file structure, and usage guidance. |

## Getting Started

This project is delivered as a static HTML interface. To view it locally, clone or download the repository and open the main HTML file in a modern web browser.

```bash
git clone <YOUR-REPOSITORY-URL>
cd Internationalizationthe
```

Then open the following file:

```text
templates/internationalization_the.html
```

For example, you can double-click the file in your file manager or open it through your browser’s **Open File** command. Keep the `static/` folder in its original location so the HTML file can load the visual assets correctly.

## Using the Platform

Begin with the **Selection Panel** to define the institution, partner, region, country, ranking group, department, or unit to review. The other tabs use the current selection to present relevant information.

| Task | Recommended tab |
|---|---|
| Set the institution, partner, region, country, or ranking group | Selection Panel |
| Obtain a high-level summary | Overview |
| Check active agreements and partner contacts | Partner Agreements |
| Review collaboration records | Activities |
| Review publications and research contributors | Research Outputs |
| Review annual departmental or unit performance | Year Report |

Within **Overview**, use the Partnership Agreements follow-up controls to find active Academic Collaboration, Research Collaboration, or Other Collaboration agreements with no recorded research outputs, activities, or student exchange. Select **Send Alert** to prepare a follow-up email for the relevant colleague or department.

## Important Notes

> The interface is intended to be used with the data and access controls provided by its hosting environment. Figures, records, and available actions may differ according to the active filters and the user’s permission level.

When updating the interface, preserve the relative paths between `templates/internationalization_the.html` and the `static/` directory. If you rename or move an asset, update its reference in the HTML file accordingly.

## Maintenance

Use the following checklist when publishing changes:

| Check | Expected result |
|---|---|
| HTML file opens in a browser | The interface loads without a blank page or broken layout. |
| Static assets load | Logos, icons, and favicon appear correctly. |
| Filter and tab labels are current | Navigation text matches the latest platform terminology. |
| Links and asset paths are valid | No missing images or broken references are displayed. |

## License

This repository does not currently include a license file. Add an appropriate license before redistributing or making the source code available for reuse.
