```markdown
# ScribeHow Embed — All Trials from Greenlight Tracker

This repository hosts a simple GitHub Pages site that embeds the ScribeHow guide "All Trials from Greenlight Tracker".

How to publish
1. Make the repository public (if it isn't already).
2. If you want a project page at `https://MSIDDIQUIEP.github.io/Instructions/`, keep the repo name `Instructions`.
3. Add `index.html` to the repository root (or put it in `docs/` and select that folder for Pages).
4. In the repository Settings → Pages, select the branch `main` (or whichever branch you push to) and the root (`/`) folder, then Save. Pages will publish within a minute or two.

Quick git commands to initialize locally and push (example)
```bash
# clone the empty repo (creates folder Instructions)
git clone git@github.com:MSIDDIQUIEP/Instructions.git
cd Instructions

# create the files (or copy the provided index.html, README.md, .nojekyll)
# then:
git add .
git commit -m "Add GitHub Pages site embedding ScribeHow guide"
git branch -M main
git push -u origin main
```

If the repo was created on the web and empty, the git push above will create the initial main branch and upload the files.

Notes
- If you want the site at the user root `https://MSIDDIQUIEP.github.io/` rename the repository to `MSIDDIQUIEP.github.io`. Otherwise the project site will be at `https://MSIDDIQUIEP.github.io/Instructions/`.
- A `.nojekyll` file is included below to prevent Jekyll processing if you need it.
```