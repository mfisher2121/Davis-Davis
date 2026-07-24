# Deployment

## GitHub Pages

1. Create a new GitHub repository.
2. Upload every file in this repository.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Save.

GitHub will publish the site from `index.html`.

---

## Vercel

Import the GitHub repository into Vercel.

No framework preset or build command is required.

Recommended settings:

```text
Framework Preset: Other
Build Command: leave blank
Output Directory: .
```

---

## Netlify

Import the repository from GitHub.

Recommended settings:

```text
Build command: leave blank
Publish directory: .
```

---

## Cloudflare Pages

Connect the repository.

Recommended settings:

```text
Framework preset: None
Build command: leave blank
Build output directory: /
```

---

## Custom domain

After deployment, point a subdomain such as:

```text
davis.mbraceintelligence.com
audit.mbraceintelligence.com
davisanddavis.mbraceintelligence.com
```

to the deployment provider.

For a prospect-specific outreach asset, a dedicated subdomain usually feels more intentional than a long path on a general website.
