# Adding your photos and videos

This site loads your real photos and videos directly from files — no upload buttons, no code editing required. Just drop your files into the matching folder below, using the exact filename listed, and refresh the page.

If a file is missing, that slot automatically shows a placeholder with the expected filename — so you'll always know exactly what's missing and where it goes.

## Folder structure

```
portfolio/
├── index.html
└── assets/
    ├── profile/
    │   └── profile.jpg              ← your headshot/profile photo
    ├── photography/
    │   ├── event-1.jpg              ← Events (tall card)
    │   ├── portrait-1.jpg           ← Portrait
    │   ├── brand-1.jpg              ← Brand shoot
    │   ├── event-2.jpg              ← Events (wide card)
    │   └── photoshoot-1.jpg         ← Photoshoot
    ├── videography/
    │   ├── social-reel-1.mp4        ← Social reel (wide card)
    │   ├── edit-reel-1.mp4          ← Edit reel
    │   ├── event-recap-1.mp4        ← Event recap
    │   ├── vertical-edit-1.mp4      ← Vertical edit (tall card)
    │   └── campaign-1.mp4           ← Campaign
    └── technical/
        ├── data-project-1.jpg       ← Data analysis project screenshot
        └── web-project-1.jpg        ← Web development project screenshot
```

## How to add a file

1. Find the slot you want to fill in the list above.
2. Rename your photo or video to match the exact filename shown (e.g. `event-1.jpg`).
3. Drop it into the matching folder.
4. Refresh the page — the placeholder disappears and your real photo/video takes its place.

## Notes

- **Photos**: use `.jpg` or `.png`. Recommended: compress large photos before adding them (under ~500KB each) so the site loads fast — tools like Squoosh.app or TinyPNG work well.
- **Videos**: use `.mp4`, ideally already compressed for web (most phone exports already are). Large video files (over ~20-30MB) will slow the page down — consider trimming or compressing if your file is large.
- **Want more than one of a kind** (e.g. a 6th photography shot)? Duplicate one of the existing work-card blocks in `index.html` and point it at a new filename — happy to do this for you if you tell me how many extra slots you want.
- **Hosting**: if you host this online (e.g. via Netlify, Vercel, GitHub Pages, or your own server), make sure you upload the entire `assets/` folder alongside `index.html` — the images won't show up if only the HTML file is uploaded.
