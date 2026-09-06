# Suman Adhikari — Professional Portfolio

## Files
- `index.html` — Home
- `about.html` — About, education, skills, projects and certifications
- `contact.html` — Contact information and email form
- `style.css` — Responsive design
- `assets/profile.png` — Profile photo

## Important GitHub Pages fix
The old portfolio used Windows computer paths such as:
`F:\Portfolio\Gemini_Generated_Image_ywmxh4ywmxh4ywmx.png`

That path only exists on your own PC, so GitHub Pages cannot load it.

This version uses:
`assets/profile.png`

All website paths are relative and GitHub-friendly.

## Upload to GitHub
Upload these files/folders while keeping the structure exactly like this:

suman-professional-portfolio/
├── index.html
├── about.html
├── contact.html
├── style.css
└── assets/
    └── profile.png

Make sure the filenames and capital letters match exactly.

Then enable:
GitHub repository → Settings → Pages → Deploy from branch → `main` → `/ (root)` → Save.

## Certificate images
I removed the old broken certificate-image paths because those image files were not included with the uploaded files. The certification information is displayed as clean professional cards instead. If you have the actual certificate images, place them in `assets/` and they can be added later.
