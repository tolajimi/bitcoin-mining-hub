# Bitcoin Mining Hub

Sleek dark-themed promotional site for the **GoMining** referral program.

**Referral code:** `awW0t`  
**Referral link:** https://gomining.com/?ref=awW0t

## Features

- Live Bitcoin price (CoinGecko)
- Live Crypto Fear & Greed Index (alternative.me)
- Educational sections about digital Bitcoin mining
- Clear multi-placement CTAs with the referral code
- Fully responsive, pure static HTML/CSS/JS (no build step)

## Deploy to Netlify (recommended)

### Option A – One-click from GitHub (easiest)

1. Go to [https://app.netlify.com](https://app.netlify.com) and log in (or sign up).
2. Click **Add new site** → **Import an existing project**.
3. Choose **GitHub** and authorize if needed.
4. Select the repository: `tolajimi/bitcoin-mining-hub`.
5. Leave build settings empty (this is a static site):
   - **Build command:** *(leave blank)*
   - **Publish directory:** `/` or `.` (root)
6. Click **Deploy site**.

Netlify will give you a free `*.netlify.app` URL instantly. You can later add a custom domain.

### Option B – Netlify CLI

```bash
npm install -g netlify-cli
netlify login
netlify init   # or netlify deploy --prod
```

### Option C – Drag & Drop

1. Download/clone this repo.
2. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop).
3. Drag the entire folder onto the page.

## Local preview

Just open `index.html` in a browser, or run a simple static server:

```bash
npx serve .
# or
python3 -m http.server 8000
```

## Customization

- Change the referral code/link in `index.html` (search for `awW0t`).
- Colors and fonts are controlled by CSS variables at the top of the `<style>` block.
- The live data scripts are at the bottom of the file.

## License

Public promotional site. Use and modify freely for your own referral marketing.
