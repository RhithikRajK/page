# RHITHIK RAJ K Portfolio

Static portfolio site ready for GitHub Pages.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Push this folder to the `main` branch.
3. On GitHub, open the repository settings.
4. Go to **Pages**.
5. Set **Build and deployment** to **GitHub Actions**.
6. The workflow in `.github/workflows/deploy.yml` will publish the site automatically on every push to `main`.

### Manual push steps

If you have not pushed yet, run:

```bash
git init
git branch -M main
git add .
git commit -m "Initial portfolio site"
```

Then add your GitHub remote and push:

```bash
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

## Local Preview

Open `index.html` in a browser, or serve it locally with any static server.

## Files

- `index.html` - Portfolio content and interaction script
- `styles.css` - Page styling and animations
