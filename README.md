# Wedding e-invitation

A single-page animated wedding invitation (envelope opening, falling petals, countdown, directions).

## Project structure

```
wedding-invite/
├── index.html
├── README.md
└── images/
    ├── seal.jpg      envelope seal (the green and gold "K" image)
    ├── photo1.jpg    cover photo (optional)
    ├── photo2.jpg    gallery photos (optional)
    ├── photo3.jpg
    ├── photo4.jpg
    └── photo5.jpg
```

Images are picked up automatically from the `images/` folder. Any of `.jpg`, `.jpeg`, `.png` or `.webp` works. If a file is missing, that part is simply skipped (no seal image means the emerald "K&V" seal is shown, no photos means no gallery).

To change an image, replace the file in `images/` with the same name.

## Deploy on GitHub Pages

1. Create a new repository on GitHub and push this folder to it.
2. Open the repository, go to **Settings**, then **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute your site will be live at `https://<your-username>.github.io/<repository-name>/`.

Open that link, adjust the details if needed, tap **Preview**, then **Copy share link** to send the invitation on WhatsApp.
