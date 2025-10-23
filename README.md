# drewyon.com — Final Links Build

This build includes your hero image and wired-in links:
- Facebook
- TikTok
- YouTube

## Deploy to GitHub Pages (quick)
**Web UI**
1. Create a new public repo named **drewyon.com** on GitHub.
2. Upload all files to the repo root.
3. Settings → Pages → set Branch = `main`, folder = `/ (root)`.
4. Your site will publish at `https://<your-username>.github.io/drewyon.com/`.
5. (Optional) Add your custom domain `drewyon.com` in Pages and follow the DNS prompts.

**Command line**
```bash
mkdir drewyon.com && cd drewyon.com
git init
git remote add origin https://github.com/<your-username>/drewyon.com.git
# copy these files into the folder, then:
git add .
git commit -m "Initial commit: final links build"
git branch -M main
git push -u origin main
```

## Password
See `PASSWORD.txt` (SHA-256 embedded in `index.html`). For stronger security, use Netlify Basic Auth or host-level protection.
