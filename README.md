# Organometallic Chemistry — Seminar Progress Tracker

A standalone progress tracker for the Winter 2026–2027 seminar literature review.

## Publish using GitHub Pages

1. Create a new **public** GitHub repository (for example, `seminar-progress-tracker`).
2. Upload `index.html` to the **root** of the repository and commit the change.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. After GitHub Pages publishes, share the URL shown in the Pages settings. For a standard project repository it normally looks like `https://YOUR-USERNAME.github.io/seminar-progress-tracker/`.

No build tools, dependencies, hosting account for students, or server are required beyond GitHub Pages.

## Student privacy and progress

- Checkboxes, notes, and the optional personal draft target are stored in the browser via `localStorage`.
- Progress is **per browser/device** and is **not** transmitted to GitHub or the instructor.
- Students can export/import a JSON backup through the tracker. Clearing browser data can erase locally saved progress.
- The tracker is optional; the final submission deadline is **January 31, 2027** and writing in English is mandatory.

## Files

- `index.html` — complete self-contained tracker (HTML + CSS + JavaScript).

## Maintenance

Edit `index.html` to update text or dates and commit. Existing student progress in the same browser remains stored under the current localStorage key, provided the published site URL/origin does not change.
