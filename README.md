# Divakar Sahani — Personal Portfolio Website

A responsive personal portfolio built with HTML, CSS and vanilla JavaScript. Includes an admin dashboard, profile-photo upload, editable profile details, skills and projects, plus JSON backup/restore.

## Run it
1. Extract the ZIP folder.
2. Open `index.html` in a modern browser. For best results, use VS Code + the Live Server extension.
3. Click **Admin** to open the dashboard.

## Demo admin login
- Username: `admin`
- Password: `admin123`

**Important:** This is a front-end-only demo. The demo login is not secure authentication. Edits are stored in that browser's localStorage and are not automatically shared across devices or visitors. For a public website with secure admin login and shared updates, connect a backend/database and deploy it with HTTPS. Uploaded images are stored in browser localStorage; keep them under 3 MB. Export a JSON backup before clearing browser data.

## Admin dashboard
- Update name, headline, bio, about text, email.
- Upload a replacement profile image.
- Edit skills one category per line: `Category: item, item`.
- Edit projects one per line: `Title | Description | Tech stack`.
- Export/import website data as JSON or reset to original content.

## Files
- `index.html` — page structure
- `styles.css` — responsive dark theme and layout
- `script.js` — editable content, rendering and admin interactions
- `assets/divakar-photo.jpg` — supplied portrait
- `assets/certificate.jpg` — supplied training certificate
