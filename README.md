# moving-up-site

Privacy policy and support pages for the Moving Up app

Public pages for the **Moving Up** iPhone app, served with GitHub Pages:

- `index.html`: landing page
- `privacy-policy.html`: privacy policy (App Store Connect → Privacy Policy URL)
- `support.html`: support page (App Store Connect → Support URL)

Other apps have their own folders with `privacy-policy.html` and `support.html`: `wardrope/` (Wardrope), `cure/` (Cure) and `conductor/` (Conductor, which also has its `icon.png`).

The Moving Up source copies live in the app repo under `docs/`. Edit them there, then copy them here.

## Publishing a change

GitHub Pages serves this repo's `main` branch, so publishing is a push:

```bash
cd moving-up-site
git add conductor              # or whichever folder changed
git commit -m "Conductor privacy and support pages"
git push
```

The pages update within a minute or two (the Actions tab shows the "pages build and deployment" run). Open the URLs to check, then paste them into App Store Connect.

| App | Privacy Policy URL | Support URL |
|---|---|---|
| Moving Up | https://movingupapp.github.io/moving-up-site/privacy-policy.html | https://movingupapp.github.io/moving-up-site/support.html |
| Conductor | https://movingupapp.github.io/moving-up-site/conductor/privacy-policy.html | https://movingupapp.github.io/moving-up-site/conductor/support.html |
| Cure | https://movingupapp.github.io/moving-up-site/cure/privacy-policy.html | https://movingupapp.github.io/moving-up-site/cure/support.html |
| Wardrope | https://movingupapp.github.io/moving-up-site/wardrope/privacy-policy.html | https://movingupapp.github.io/moving-up-site/wardrope/support.html |

**First time only** (already done for this repo): Settings → Pages → Source: *Deploy from a branch*, Branch: `main`, folder `/ (root)`. The repo must be public on a free account.
