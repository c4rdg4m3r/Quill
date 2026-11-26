# Quill

A calm, responsive learning website for mathematics and science across elementary, middle, and high school grades.

## Deploy on Render

The website is currently packaged in `quill-learning-website.zip`. Render extracts it during the build and publishes the `quill-learning/` folder.

### Render settings

- **Repository:** `c4rdg4m3r/Quill`
- **Branch:** `main`
- **Root Directory:** leave blank
- **Build Command:** `unzip -o quill-learning-website.zip -d .`
- **Publish Directory:** `quill-learning`

The included `render.yaml` contains these settings for Render Blueprint deployments.

## Features

- Math and science lessons for elementary, middle, and high school
- Grade and subject filters
- Lesson search
- Short explanations and quick-check quizzes
- Progress saved in the visitor's browser using local storage
- Light and dark theme settings

No environment variables or backend services are required. Progress and theme preference are stored separately in each visitor's browser.
