## Quick Start
1. **Copy files** into your repo.
2. Go to **Settings → Pages** and select `main` branch, `/ (root)`.
3. Wait a minute, then open the URL GitHub shows you (e.g. `https://USERNAME.github.io/my-site/`).


## Custom Domain (Optional)
- Buy a domain (e.g., from Namecheap/GoDaddy).
- Add a DNS `CNAME` record pointing `www.yourdomain.com` → `USERNAME.github.io`.
- Create a file named `CNAME` at the repo root containing only your domain: `www.yourdomain.com`.
- In **Settings → Pages**, enable **Enforce HTTPS**.


## Common Fixes
- Add a file named `.nojekyll` (empty) if assets don’t load.
- For single‑page apps, include `404.html` to client‑side redirect.
