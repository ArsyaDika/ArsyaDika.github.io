# Site maintenance notes

This site is a single static page with no build step. To add a project, save a preview image in `assets/img/`, add one block to `projects.yml`, then commit and push. GitHub Pages updates the site within 1 to 2 minutes. The workflows shown in the "Automation" section are configured in `automation.yml`.

Run locally with `python -m http.server 8000`, then open http://localhost:8000.

Built with HTML, CSS and JavaScript · MapLibre GL JS · js-yaml · OpenFreeMap
