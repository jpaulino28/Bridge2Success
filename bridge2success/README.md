# Bridge 2 Success

Static website for the Bridge 2 Success college access program.

## Run locally

Open `index.html` in a browser, or:

```bash
cd ~/Projects/bridge2success
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Application form

The **Apply** page links to the official Google Form (configured in `index.html` as `APPLICATION_FORM_URL`).

## Assets

- `assets/logo.png` — Bridge 2 Success logo
- `assets/eboard/*.jpg` — executive board photos
- `assets/advisors/*.jpg` — advisor headshots
- `advisors.js` — advisor names, schools, majors, and roles

## Deploy

Upload the project folder to GitHub Pages, Netlify, or any static host. Keep folder structure intact so image paths resolve.
