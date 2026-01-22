# Winter AR — Snowmen & Pine Trees (A‑Frame WebXR)

This project is a **winter-themed augmented reality** scene built with **A‑Frame**. It lets you place **snowmen** and/or **pine trees** on a **flat horizontal surface** (floor, desk) using **WebXR hit‑test** in supported Android browsers.

## Features

- ☃️ Procedural **snowman** made from spheres/cylinders/cones (no 3D assets needed).
- 🌲 Procedural **pine tree** made from cones + trunk.
- Two interaction modes:
  - **Spawn** (bonus): each tap spawns a new object.
  - **Move**: tap to move a single preview object.

## Run it (AR requirements)

WebXR AR hit‑test requires the page to be served over **HTTPS** and works best on **Chrome on Android**.

### Deploy via GitHub Pages (recommended)

1. Fork the template repo and copy these files into your fork.
2. In your repo: **Settings → Pages → Deploy from a branch → Branch: `main` / folder: `/ (root)`**.
3. Wait ~1 minute. Your site will be available at:

`https://YOUR_GITHUB_USERNAME.github.io/aframe-ar-example/`

Open the link on your **Android phone** in **Chrome**, press **AR**, and scan the floor/desk.

## Notes

- The `ar-hit-test` component is used to find real‑world surfaces and to fire selection events.
- The built-in A‑Frame primitive geometries are used to construct winter objects.

