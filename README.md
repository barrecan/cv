# Nick Barreca CV

Static resume site styled after Jacob Harris's resume page.

## Local development

```sh
python3 -m http.server 4173
```

Open `http://localhost:4173`.

Edit `index.html` for resume content and `static/css/layout.css` for styling.

## Deployment

GitHub Pages is deployed from the `main` branch by GitHub Actions. In the repository settings, set Pages to use **GitHub Actions** as the publishing source and configure the custom domain as `barrecan.com`.

Pull requests run static file validation before merge. Dependabot checks GitHub Actions weekly.
