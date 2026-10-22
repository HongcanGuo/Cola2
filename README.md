# Cola2 Project Page

Static project page for **Cola2: Co-Adaptive Hierarchical Language Modeling with Continuous Semantic Compression and Balanced Discrete Generation**.

The page is static and has no build step. The original Cola frontend CSS/JavaScript and all figures required at runtime are bundled under `static/`, so the deployed page has no dependency on `ref/`.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open:

- English: <http://localhost:8000>
- 中文: <http://localhost:8000/zh/>

## Structure

```text
.
├── index.html
├── zh/
│   └── index.html
├── static/
│   ├── css/index.css
│   ├── js/index.js
│   ├── images/
│   │   ├── cola_logo.png
│   │   ├── cola2-workflow.svg
│   │   ├── favicon.svg
│   │   └── figures/
│   └── videos/
│       └── cola2-v2-motion-bgm-1080p.mp4
```

The `ref/` directory can be removed without affecting either language version.

## Add links later

The Paper, arXiv, Code, and Model controls use the original page's disabled-link pattern. When links are ready, update each corresponding `<a class="btn is-soft" href="#">`: replace `#` with the URL, remove `is-soft`, and remove its `coming-soon-badge`.

Also replace `note = {Paper link forthcoming}` in the BibTeX block with the final venue or arXiv metadata.
