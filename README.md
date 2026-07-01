# Rahul Kumar Gautam — Personal Site

A single-page site with education, activity record, and a downloadable CV.

## Structure

```
.
├── index.html                # the whole site (no build step)
├── Rahul_Gautam_CV.docx      # downloadable CV (kept at repo root — no folder needed)
└── README.md
```

## Running locally

Just open `index.html` in a browser — no server or build tools required.

## Publishing on GitHub Pages

1. Create a new repository and push these files to the root (or to a `main` branch).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Choose the `main` branch and `/ (root)` folder, then **Save**.
5. GitHub will publish the site at:
   `https://<your-username>.github.io/<repo-name>/`
   (usually live within a minute or two).

## Updating the CV

Replace `Rahul_Gautam_CV.docx` (at the repo root) with a new file of the **same
name** and commit — the download button on the site will automatically serve
the new version. If you rename the file, update the `href` in the three places
it's referenced inside `index.html` (search for `Rahul_Gautam_CV.docx`).
