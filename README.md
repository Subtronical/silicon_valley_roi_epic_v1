# SST Group Website

Silicon Valley residential construction — Builds · ADUs · Renovations · Property Management.

## Deployment

This is a single-file static website hosted on **GitHub Pages**.

### To publish:

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select **Deploy from a branch**
4. Set branch to `main`, folder to `/ (root)`
5. Click **Save** — site goes live at `https://YOUR-USERNAME.github.io/sst-website/`

### Custom domain (optional):

1. Add a `CNAME` file with your domain (e.g. `sstgroup.com`)
2. Point your domain DNS to GitHub Pages IPs:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
3. Or use a CNAME record pointing to `YOUR-USERNAME.github.io`

## Structure

```
index.html    ← entire site (single file, self-contained)
.nojekyll     ← tells GitHub Pages to skip Jekyll
CNAME         ← add your custom domain here (optional)
README.md     ← this file
```

## Tech

- Pure HTML/CSS/JS — no build step, no dependencies
- Chart.js loaded from CDN for Market Pulse charts
- All images (logo, project photos) embedded or loaded from MLSListings/Zillow CDN
- Works offline except for CDN-hosted chart library and listing photos

## Pages

| Tab | Description |
|-----|-------------|
| Home | Overview, city cards, services |
| Construction Costs | Per-city cost breakdown with converter |
| Our Model | Project types with interactive city/size selector |
| Market Visual | Bubble chart, challenger quadrant, buyer vs seller |
| Permits | 10-jurisdiction permit guide |
| Projects | West San Jose & Fremont Mission Hills portfolio |
| Market Pulse | Chart.js historical + projected price data |
| ROI: Owner | Upgrade / Rebuild / ADU / Sell calculators |
| ROI: Investor | Flip / Rebuild / Renovate & Hold / ADU models |
| Tenancy | Rent tables, Airbnb data, CA tenancy laws |
| Contact | Qualifying inquiry form |

---
Data sources: MLSListings, Redfin, Zillow, Apartments.com, Zumper, Airbtics (2025)
