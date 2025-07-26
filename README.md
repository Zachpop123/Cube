# Interactive 3D Wireframe Cuboid

This repository hosts an interactive 3D cuboid editor using Three.js and dat.GUI.  
Corner nodes can be dragged or set via GUI, edges can be resized, and clicking an edge shows its angles relative to the XY, XZ, and YZ planes.

## How to Deploy on GitHub Pages

1. **Create** a new GitHub repository (e.g. `my-cuboid-editor`).
2. **Copy** `index.html` and `README.md` into the repo root.
3. **Commit** and **push** to `main`:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial cuboid editor"
   git branch -M main
   git remote add origin https://github.com/<your-username>/my-cuboid-editor.git
   git push -u origin main
