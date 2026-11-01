# ICG Visualization Toolkit

Interactive visualizations for an Introduction to Computer Graphics course. Every tool is a standalone HTML page with no build step and no dependencies, apart from Google Fonts with system-font fallbacks.

## Tools

| Tool | Topic | What it shows |
|---|---|---|
| [Pipeline Exam Map](tools/pipeline-map.html) | Overview | Pipeline stages from model transform to frame buffer, with the topics at each stage |
| [Projection Explorer](tools/projection-explorer.html) | Ch3 Viewing | A cube, its projectors, and the projection plane in 3D, plus the image on the plane. Multiview, isometric, dimetric, trimetric, oblique, and 1/2/3-point perspective. The side camera rotates 360° |
| [Phong Vectors](tools/phong-vectors.html) | Ch4 Shading | n, l, r, v at a surface point, and the three Phong reflection terms |
| [Orbit Animation Builder](tools/orbit-animation.html) | Ch2 Transformations | The midterm animation problem: build `T·Ry(u)·T·Ry(90)` right to left, see what wrong orders do, attach a rolling second model, and view through its eye with `Inv(M)` |
| [Phong Sphere Lab](tools/phong-sphere-lab.html) | Ch4 Shading | A software-rasterized sphere. Toggle ambient, diffuse, and specular, tune k_a, k_d, k_s, and α, and switch between flat, Gouraud, and Phong shading |

## Running

Open `index.html` in a browser, or enable GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder) to get a hosted link.

## Layout

```
index.html          landing page
assets/common.css   shared colors, type, and dark mode
tools/*.html        one file per visualization
```
