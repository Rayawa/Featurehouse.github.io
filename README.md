# Featurehouse.github.io

English | [简体中文](README_zh.md)

A static documentation website for the Sweet Potato mod and related integration resources.

Archived project retained for reference.

## Overview

The repository contains mod descriptions, a gallery, wiki pages and integration-standard documentation. English and Chinese page variants share static styles and media.

## Technology and Dependencies

HTML and CSS, with GitHub Pages/Jekyll configuration in `_config.yml`. Local preview needs only a static HTTP server; Python 3 can provide one.

## Repository Structure

- `index.html` — default landing page
- `en/` — English pages
- `zh/` — Chinese page resources
- `spm/` — mod descriptions and wiki
- `pigeonia-linkage-standard/` — integration-standard pages
- `static/` — styles and media

## Quick Start

Serve the repository root so absolute asset paths resolve correctly:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000/`. Edit the HTML and assets directly; no frontend build is required.

Open `/en/` for the English site. The documentation can also be served by GitHub Pages.
