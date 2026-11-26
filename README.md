# Quill

A calm, responsive learning website for mathematics and science across elementary, middle, and high school grades.

## Deploy on Render

This repository stores the site in `quill-learning-website.zip`. The included `render.yaml` tells Render to extract that archive and publish the `quill-learning/` folder.

### Recommended: deploy using the Blueprint

1. Open https://dashboard.render.com/blueprints.
2. Choose **New Blueprint Instance**.
3. Connect the GitHub repository `c4rdg4m3r/Quill`.
4. Render will read `render.yaml` and configure the static site.
5. Review the settings and deploy.

### Or create a Static Site manually

Use these settings:

- **Repository:** `c4rdg4m3r/Quill`
- **Branch:** `main`
- **Root Directory:** leave blank
- **Build Command:** `unzip -o quill-learning-website.zip -d .`
- **Publish Directory:** `quill-learning`

Do not leave the build command blank: the site files are inside the ZIP archive.

## Features

- Math and science lessons for elementary, middle, and high school
- Grade and subject filters
- Lesson search
- Short explanations and quick-check quizzes
- Progress saved in the visitor's browser using local storage

No environment variables or backend services are required. Progress is stored separately in each browser and is not synchronized between devices.
