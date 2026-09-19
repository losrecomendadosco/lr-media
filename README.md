# LR Media

Shared media library for Los Recomendados developers.

Use this repository to store and reuse approved images, videos, audio, documents, and other static assets across LR projects.

## Upload from GitHub Mobile

1. Open this repository in the GitHub mobile app.
2. Open the folder that matches the asset type.
3. Tap **Add file** → **Upload files**.
4. Select the media from your device.
5. Use a clear commit message, such as `Add summer campaign hero image`.
6. Commit directly to `main` for routine uploads, or create a branch/pull request when review is needed.

Keep uploads organized using the folder layout below. GitHub Mobile preserves the folder structure when you upload files.

## Folder layout

```text
images/
  brand/       Logos, marks, icons, and brand assets
  social/      Posts, stories, thumbnails, and campaign graphics
  web/         Website and product images
  misc/        Images that do not fit another category
videos/
  social/      Short-form and social videos
  promos/      Promos, trailers, and campaign videos
  misc/        Other videos
audio/         Music, voiceovers, podcasts, and sound effects
documents/     PDFs, briefs, guidelines, and reference files
other/         Assets that do not fit another category
```

## Naming files

Use lowercase names with hyphens and include useful context:

```text
<project>-<purpose>-<date-or-version>.<extension>

website-home-hero-2026-09.jpg
campaign-fall-reel-v2.mp4
brand-logo-white.svg
```

Avoid spaces, special characters, vague names such as `final-final.png`, and filenames that contain private information.

## Media guidelines

- Upload only assets that the organization is allowed to use.
- Do not commit passwords, API keys, personal data, or confidential material.
- Prefer web-friendly formats: WebP/JPEG/PNG for images and MP4 (H.264/AAC) for video.
- Compress media before uploading when practical.
- Keep individual files below GitHub's 100 MB hard limit. Large files should use an approved external asset store instead of Git history.
- Do not replace or delete an asset that another project may use without checking its references.
- Add a short description in the commit message; use a pull request when an asset needs approval.

## Using an asset

Each file has a stable GitHub URL. Open the file on GitHub and use **Copy permalink** when you need a version-pinned link. For public assets, the raw URL can be used by applications that are allowed to fetch GitHub-hosted files.

## Contributions

See [CONTRIBUTING.md](CONTRIBUTING.md) for the upload checklist and review guidance.
