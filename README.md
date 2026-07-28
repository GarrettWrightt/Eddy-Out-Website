# Eddy Out Environmental — deploy

Static site. No build step, no framework, no dependencies to install.

## Files
All files sit flat in the repo root: index.html, support.js, and the .jpeg/.png images.
index.html references the images by bare filename, so keep them in the same folder.

## Deploy to Vercel
1. Upload every file in this folder to the repo root (no subfolders).
2. On Vercel: Add New > Project > import the repo.
3. Framework preset: **Other**. Build command: leave empty. Output directory: **./**
4. Deploy. Free tier is enough for this site.

## Custom domain
Vercel > Project > Settings > Domains > add eddyoutenv.com, then point the
registrar's nameservers or A/CNAME records at the values Vercel shows.

## Editing later
Change index.html and re-deploy (push to the repo, or drag the folder again).
