# ASME PONGO

**Professional Outreach & Network Geographic Overview**

> Mapping ASME Professional and Student Sections, jurisdictions, and geographic reach across the United States.

Created by **J. Manuel Melendez**

## Overview

ASME PONGO is an interactive geographic planning dashboard for exploring ASME Professional Sections and Student Sections across the continental United States.

The dashboard includes:

- Professional Section headquarters
- Student Section campus locations
- Separate modeled-radius controls for Professional and Student Sections
- Official Professional Section county/parish jurisdiction overlays
- Partial-county jurisdiction indicators
- Multi-section selection
- State and territory filters
- Modeled coverage, overlap, and gap analysis
- Nearest Professional Section analysis
- Expansion-hub simulation
- CSV export
- PNG map export
- Shareable URL settings

## Run Locally

Open `index.html` in a modern browser such as Chrome, Edge, Firefox, or Safari.

An internet connection is required because PONGO loads mapping libraries and U.S. geographic boundary data from public CDNs.

## Deploy with GitHub Pages

1. Create a new GitHub repository, for example:
   `asme-pongo`
2. Upload all files from this folder to the repository root.
3. Open the repository on GitHub.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select:
   - Branch: `main`
   - Folder: `/ (root)`
7. Click **Save**.
8. GitHub will publish the site at an address similar to:

   `https://YOUR-USERNAME.github.io/asme-pongo/`

## Recommended Repository Description

`ASME PONGO — Professional Outreach & Network Geographic Overview. Interactive mapping of ASME Professional and Student Sections, jurisdictions, and geographic reach across the United States.`

## Suggested Topics

`asme`, `engineering`, `geospatial`, `mapping`, `professional-sections`, `student-sections`, `github-pages`

## Documentation

The current user guide is available at:

`docs/ASME_PONGO_User_Guide.pdf`

## Data Notes

PONGO combines different geographic concepts:

- **Professional Section jurisdiction**: county/parish territory mapped from ASME Professional Section descriptions.
- **Professional modeled reach**: adjustable distance-based planning radius around a Professional Section headquarters.
- **Student modeled reach**: adjustable distance-based planning radius around a Student Section campus location.

Modeled reach should not be interpreted as official ASME jurisdiction.

Professional and Student Section information can change over time. Verify current ASME records before using PONGO output for formal organizational decisions.

## Author

**J. Manuel Melendez**

## Version

Initial GitHub Pages package: 2026-08-11
