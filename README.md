# Zijun Wang — Academic Homepage

Source for [zijun-wang0823.github.io](https://zijun-wang0823.github.io/). The site is dependency-free and can be served directly by GitHub Pages.

## Local preview

From this directory, run:

```powershell
python -m http.server 8000
```

Then open `http://127.0.0.1:8000/`.

## Content updates

- Profile, education summary, news, research areas, publications, and projects are in `index.html`.
- Global colors, typography, layout, responsive behavior, and focus states are in `assets/style.css`.
- Replace the stable CV file at `assets/cv/Zijun_Wang_CV_Wireless_Algorithms_Testbed.pdf` when a new CV is ready; the HTML link does not need to change.
- When replacing the portrait or testbed photograph, export optimized JPEG and WebP versions into `assets/images/` using the existing filenames.
- Asset provenance is documented in `ASSET_SOURCES.md`.

## Publication policy

The homepage follows Zijun Wang's Google Scholar profile: a paper is included when it appears there, including indexed arXiv preprints. Resume-only submitted or ongoing work is not added until it is visible on Scholar.

## Publishing

GitHub Pages can serve the repository root from the `main` branch. Review the local build before committing or pushing changes.
