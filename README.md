# Voters Website (BPY Team Mamidipally)
This is a static site to display voter list with English <-> Telugu toggle.

## Files
- `index.html` - main site (open as root)
- `voters.csv` - your CSV data (must be present)
- `images/Logo.jpeg` - site logo

## How to publish on GitHub Pages
1. Create a new public repository on GitHub (e.g., `voters`).
2. Upload all files from this folder to the repository root (or push via git).
3. In the repository go to **Settings → Pages** and set **Branch: main**, **Folder: / (root)** then Save.
4. Wait ~1 minute and your site will be available at: `https://<username>.github.io/<repo-name>/`

## Notes
- Ensure `voters.csv` is in the same folder as `index.html` on GitHub.
- If you generated `voters_telugu.csv`, you can include that instead and the page will prefer it.
- If you want a custom domain, configure `CNAME` in repo settings and add DNS records accordingly.
