# Rohith Portfolio

Static portfolio site for Customer Success Manager applications.

## Files

- `index.html`: main page
- `styles.css`: layout and styling
- `script.js`: reveal-on-scroll animation
- `resume/RohithPM.pdf`: downloadable resume

## Preview locally

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy options

### GitHub Pages

This repo is configured for GitHub Pages with a workflow in `.github/workflows/deploy-pages.yml`.

Expected URL:

```text
https://rpm6105-cmd.github.io/rohith-portfolio/
```

To enable it:

1. Open the repository settings on GitHub.
2. Go to `Pages`.
3. Under `Build and deployment`, choose `GitHub Actions` as the source.
4. Push to `main` and GitHub will deploy automatically.

### Netlify

1. Drag the `portfolio` folder into Netlify Drop, or connect the folder to a repo.
2. Publish directory: `.`
3. No build command needed.
4. `netlify.toml` is already included.

### Vercel

1. Import the folder or repo into Vercel.
2. Framework preset: `Other`
3. No build command needed.
4. Output directory: `.`
5. `vercel.json` is already included.

### GitHub Pages

1. Push the `portfolio` folder contents to a repository root.
2. In repository settings, enable GitHub Pages from the `main` branch root.
3. The page will be served as a static site.

## Customization

- Replace `assets/profile-mark.svg` with your real profile photo if you want a more personal hero section.
- Update contact links in `index.html` if you want to add GitHub later.
- Add screenshots to the CX Retention Tool section if you want stronger project proof.
