# Hoonmin Kim — Profile and technical writing

Hugo site using **Blowfish v3.9.0**, vendored in `themes/blowfish`.
Requires **Hugo Extended 0.167.0**. No Node, pnpm, or Go dependency installation is needed for the bundled theme assets.

```sh
hugo server --disableFastRender
hugo --minify
```

## Content

- `content/_index.md`: homepage navigation
- `config/_default/languages.en.toml`: name, two-line headline, social links
- `content/about/index.md`: existing biography, experience, expertise, patents, languages
- `content/projects/`: project portfolio
- `content/writing/`: technical articles and theory notes
- `static/uploads/resume.pdf`: existing résumé download, retained unchanged

No author image is configured. The original image remains at `assets/originals/profile-photo-original.jpg` and is not displayed.
The original PDF and photo were carried over unchanged; theme migration does not update their contents.

The theme's precompiled assets are included. Custom CSS belongs in `assets/css/custom.css`.
To upgrade, replace the runtime files in `themes/blowfish` with a tested upstream release and update `VERSION`.
This migration changes local files only; no repository push or publication has been performed.
