# Evergreen Bank — Informational Banking Website POC

A responsive, static, informational banking landing page. **Evergreen Bank is a fictional demonstration brand**, not a financial institution.

## Website sections
- Hero and featured banking services
- Checking, savings, and fixed deposits
- Home loans, personal loans, and auto loans
- Life, health, home and auto insurance
- About / banking philosophy
- Frontend-only demonstration enquiry form (does not transmit or store submitted information)

No login, banking transactions, accounts database, APIs, or payment processing. No financial product applications are submitted.

## Run locally
Open `index.html` in your browser. No dependencies or build process.

## Fastest live site: Netlify Drop
1. Extract the ZIP, if using the downloadable archive.
2. Visit https://app.netlify.com/drop
3. Drag the **clearbank-poc folder** into the drop zone.
4. Copy the generated `.netlify.app` URL.

## Publish to GitHub
Create an empty repository (e.g. `evergreen-bank-poc`) at https://github.com/new and from the extracted folder run:

```bash
git init
git add .
git commit -m "Create informational banking website POC"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/evergreen-bank-poc.git
git push -u origin main
```

To auto-deploy from GitHub: Netlify → Add new project → Import an existing project → GitHub → choose your repository. Leave build command blank; publish directory is `.`.

Alternatively, use GitHub Pages: repository Settings → Pages → Deploy from a branch → `main` / `/(root)`.

## Important
All text is demo-only. Avoid implying a real institution, quoting rates without verification, or collecting sensitive customer information. The enquiry form deliberately displays a local-only confirmation rather than sending information.

## Files
- `index.html`: semantic website structure
- `styles.css`: responsive design
- `app.js`: mobile navigation and local-only form feedback
