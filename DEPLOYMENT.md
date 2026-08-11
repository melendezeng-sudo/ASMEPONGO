# GitHub Pages Deployment Guide

## 1. Create the Repository

Go to GitHub and create a new repository.

Recommended repository name:

`asme-pongo`

Recommended visibility:

- Public, if you want anyone with the URL to access the tool.
- Private, only if your GitHub plan and Pages configuration support your intended access model.

Do not initialize the repository with a README if you plan to upload this package directly; this package already contains one.

## 2. Upload the Files

Upload the contents of this package to the root of the repository:

- `index.html`
- `README.md`
- `docs/`

Commit the files to the `main` branch.

## 3. Enable GitHub Pages

In the repository:

1. Open **Settings**
2. Select **Pages**
3. Under **Build and deployment**, select **Deploy from a branch**
4. Select branch **main**
5. Select folder **/ (root)**
6. Save

GitHub will provide the published address after deployment completes.

Typical URL:

`https://YOUR-USERNAME.github.io/asme-pongo/`

## 4. Update PONGO Later

To publish a new version:

1. Replace `index.html` with the new PONGO build.
2. Update the user guide if needed.
3. Commit the changes to `main`.

GitHub Pages will redeploy automatically.

## 5. Optional Custom Domain

If ASME or another organization later provides a custom domain, configure it under:

**Settings → Pages → Custom domain**

Example:

`pongo.example.org`

## 6. Test Before Sharing

Verify these functions after deployment:

- Professional Section multi-select
- Student Section multi-select
- Professional radius slider
- Student radius slider
- Official jurisdiction toggle
- State/territory filters
- Overlap and gap analysis
- Professional and Student markers
- Expansion simulator
- CSV export
- PNG export
- Shareable settings URL

