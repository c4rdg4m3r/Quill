# Quill — calm learning website

A responsive, static learning website for math and science across elementary, middle, and high school grades.

## Included
- Subject filters and grade-level filtering
- Searchable lesson library
- Short explanations and quick-check quizzes
- Local progress tracking with browser localStorage
- Responsive layout for desktop, tablet, and mobile

## Run locally
Open `index.html` in a browser. No build step or server-side code is required.

## Deploy on Render
1. Create a new GitHub repository (for example, `quill-learning`).
2. Upload `index.html` and `README.md` to the repository's root.
3. Sign in to Render and choose **New + → Static Site**.
4. Connect the GitHub repository.
5. Use these settings:
   - **Name:** `quill-learning` (or any available name)
   - **Branch:** `main`
   - **Root Directory:** leave blank
   - **Build Command:** leave blank
   - **Publish Directory:** `.`
6. Click **Create Static Site**. Render will publish the site and provide a URL ending in `onrender.com`.
7. Whenever you push changes to the connected GitHub branch, Render will automatically redeploy.

No environment variables are needed. Progress is stored in each visitor's own browser and is not synced between devices.