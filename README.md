# eli-lame.github.io

Personal portfolio. Plain HTML, no build step.

- **Edit content:** open `index.html` and change the lists at the top of the first `<script>` (SITE, ABOUT, PROJECTS, EXPERIENCE, RESEARCH).
- **Photos / background:** put images in `img/`.
- **3D models:** put `.glb` files in `models/` and set `model: "models/your-part.glb"` on a project.
- **Preview locally:** `python3 -m http.server` in this folder, then open http://localhost:8000
- **Publish:** `git add -A && git commit -m "update" && git push` — the live site updates in about a minute.
