# Quill

A calm, responsive learning website for mathematics and science across elementary, middle, and high school grades.

## Deployment

The website source is stored directly in the `quill-learning/` directory. Render publishes that directory as a static site; no ZIP extraction or build step is needed.

### Render settings

- **Repository:** `c4rdg4m3r/Quill`
- **Branch:** `main`
- **Root Directory:** leave blank
- **Build Command:** `echo "Quill static files are ready"`
- **Publish Directory:** `quill-learning`

The included `render.yaml` contains these settings for Render Blueprint deployments.

## Features

- Math and science lessons for elementary, middle, and high school
- Grade and subject filters
- Lesson search
- Short explanations and quick-check quizzes
- Progress saved in the visitor's browser using local storage
- A settings control for switching between light and dark themes

No environment variables or backend services are required. Progress and theme preference are stored separately in each visitor's browser.
