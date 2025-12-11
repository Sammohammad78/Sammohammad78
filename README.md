# Mohammed Sam (Sammohammad78)

> Software Engineer | BIM & 3D Dev Enthusiast | Cloud-native builder

A clean, focused developer profile README. I removed older/unused project references (5D projects, Caribbean Azure, CQP) as requested and reorganized everything for clarity and impact.

---

## Quick summary

- Location: Remote
- Work: Open to collaboration and contract work
- Tech focus: Full-stack development, infrastructure as code, 3D/BIM automation, cloud-native deployments

---

## What I build

I design and build reliable, maintainable systems that bridge 3D BIM workflows and modern web/cloud engineering. Typical projects include:

- Automated BIM data pipelines (glTF, IFC, Revit -> web viewers)
- Interactive 3D web experiences using Three.js / model-viewer
- Cloud automation and CI/CD for engineering workloads
- Developer tools and utilities to make design data repeatable

---

## Featured projects

> NOTE: I removed older "5D projects", "Caribbean Azure" and "CQP" entries per request.

- Project A — Interactive BIM viewer
  - Tech: Three.js, React, glTF
  - Short: Fast, searchable building model viewer with layer filtering.

- Project B — BIM data pipeline
  - Tech: Python, IFC, Docker
  - Short: Extracts, normalizes and publishes IFC-derived metadata as JSON for dashboards.

- Project C — Infrastructure & tooling
  - Tech: Terraform, GitHub Actions, Docker
  - Short: Production-ready infra templates and CI for building and hosting 3D apps.

(If you want, I can add links and short demos for each project.)

---

## 3D BIM animation (interactive placeholder)

I included a modern, embeddable placeholder for a 3D BIM animation. To show an actual interactive model you can:

1. Export a glTF/glb from your BIM tool (Revit/Blender/IFC converters).
2. Upload the .glb file to your repo (e.g., under /assets/models/).
3. Replace the src in the <model-viewer> snippet below with the GitHub raw URL to your .glb file.

Embed example (works in GitHub Pages or any static site):

````markdown
<figure>
  <!-- model-viewer is supported in modern browsers. For offline/Pages use include <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script> -->
  <model-viewer src="https://raw.githubusercontent.com/Sammohammad78/Sammohammad78/main/assets/models/building.glb" alt="BIM model" auto-rotate camera-controls ar ios-src="model.usdz" style="width:100%;max-width:900px;height:500px;background:#f6f7fb"></model-viewer>
  <figcaption>Interactive BIM preview (replace with your model)</figcaption>
</figure>
````

If you prefer a rendered animation (GIF/MP4), generate it from Blender or your renderer and add it under /assets/animations/ and embed with standard Markdown:

```markdown
![BIM animation](assets/animations/bim-anim.gif)
```

If you want, I can help create a small Three.js demo and a GitHub Pages site to host and showcase it.

---

## Tech & tools

- Languages: JavaScript/TypeScript, Python
- 3D/BIM: glTF, Three.js, model-viewer, IFC, Blender
- Cloud & infra: Docker, Terraform, GitHub Actions
- Data: JSON, CSV, Postgres

---

## How to run the demo locally (example)

1. Clone the repo

   git clone https://github.com/Sammohammad78/Sammohammad78.git
2. Serve a static site (if demo uses model-viewer):

   npx serve .

3. Open http://localhost:5000 and navigate to the README or demo page.

---

## Contact

- GitHub: @Sammohammad78
- Email: (add your email)

---

## Want this even cooler?

I can:
- Build a small Three.js app that loads your glTF and provides section filtering, measurements, and animated walkthroughs.
- Create a script to export Revit/IFC to optimized glTF automatically.
- Add a GitHub Actions workflow to validate and deploy your 3D demo to GitHub Pages on push.

Tell me which of these you'd like and I will create the files and workflows.

---

*README last updated: 2025-12-11*