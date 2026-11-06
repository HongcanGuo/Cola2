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
│   ├── paper/
│   │   └── paper.pdf
│   └── videos/
│       └── cola2-v2-motion-bgm-1080p.mp4
```

The `ref/` directory can be removed without affecting either language version.

## External resources

The Paper, arXiv, Code, and Model controls all link to their published resources.
