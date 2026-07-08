# AI in Financial Services Weekly

A weekly intelligence briefing on AI in financial services, by Carl Jakobsson.

## Deploying to GitHub Pages

### Quick setup (5 minutes)

1. **Create a new GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it something like `ai-finserv-weekly` (or `yourusername.github.io` if you want it at your root domain)
   - Set it to **Public**
   - Click **Create repository**

2. **Upload the files**
   - Click **"uploading an existing file"** on the empty repo page
   - Drag and drop the entire contents of this folder:
     - `index.html` (the archive/landing page)
     - `issues/` folder (containing each issue's HTML)
   - Commit directly to the `main` branch

3. **Enable GitHub Pages**
   - Go to **Settings** → **Pages** (left sidebar)
   - Under **Source**, select **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)`
   - Click **Save**

4. **Access your site**
   - Your newsletter will be live at: `https://yourusername.github.io/ai-finserv-weekly/`
   - It typically takes 1–2 minutes for the first deploy

### Adding new issues

Each week, to publish a new issue:

1. Add the new HTML file to the `issues/` folder (e.g. `issue-5.html`)
2. Update `index.html` to add a new issue card at the top of the archive
3. Commit and push — GitHub Pages deploys automatically

### Custom domain (optional)

To use your own domain (e.g. `newsletter.yoursite.com`):

1. In **Settings** → **Pages**, enter your custom domain
2. Add a CNAME record with your DNS provider pointing to `yourusername.github.io`
3. GitHub will automatically provision an SSL certificate

### File structure

```
ai-finserv-weekly/
├── index.html              # Archive / landing page
├── README.md               # This file
└── issues/
    ├── issue-3.html         # Week of June 25 – July 1, 2026
    └── issue-4.html         # Week of July 2 – 8, 2026
```

### Features

- **Fully self-contained HTML** — no external dependencies, stylesheets or JavaScript libraries
- **"Download / Print as PDF" button** on each issue (triggers browser print dialog)
- **"Copy for LinkedIn" button** on each issue (copies a plain-text version to clipboard)
- **Email-compatible** — the same HTML files can be sent as email newsletters
- **Mobile responsive** — max-width 640px container scales cleanly on phones

## License

Content © Carl Jakobsson. All rights reserved.
