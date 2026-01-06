# Daily Nudge Public

Public-facing Telegram Mini App pages hosted via GitHub Pages.

## URLs

- **Dev:** https://ozzzzz.github.io/daily_nudge_public/dev/
- **Prod:** https://ozzzzz.github.io/daily_nudge_public/prod/

## Deployment

### Deploy to dev

Copy from main project and push:

```bash
cp ../daily_nudge/webapp/index.html dev/
git add dev/index.html && git commit -m "Update dev" && git push
```

### Promote dev to prod

When dev is tested and ready:

```bash
cp dev/index.html prod/
git add prod/index.html && git commit -m "Promote to prod" && git push
```

## Setup (one-time)

1. Go to repo Settings → Pages
2. Set Source to **GitHub Actions**
