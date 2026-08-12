# Research website

This repository contains the static GitHub Pages site for MuJoCo Hello Gripper.

## Preview locally

From the repository root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy

The workflow at `.github/workflows/pages.yml` publishes the repository on every push to `main`. GitHub Pages uses **GitHub Actions** as its deployment source.

The expected project URL is:

```text
https://waterloo-visuomotor.github.io/
```

## Media

Web-sized copies live under `assets/media/`, with poster frames in `assets/posters/`. The source media is not modified. Videos are encoded to a browser-friendly 960×540 preset to keep the published site responsive.
