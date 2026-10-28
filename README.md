# ATV Powerchair — Patented Powerchair Swing Arm Suspension (`atvpowerchair.com`)

Static landing page presenting **U.S. Patent No. US 10,772,776 B2** (*Sept. 15, 2020*) for an independent swing arm suspension system with adjustable air ride for powerchairs, along with three embedded Vimeo demonstration videos.

- **Target Domain:** [www.atvpowerchair.com](https://www.atvpowerchair.com)
- **Contact Email:** [handipowerchair@pm.me](mailto:handipowerchair@pm.me)
- **Patent Number:** US 10,772,776 B2 (Issued Sept. 15, 2020)
- **Asking Price:** $200,000

## Included Videos

1. **See how the patented suspension works video** — `https://vimeo.com/692428665`
2. **Handi-powerchair info video** — `https://vimeo.com/883616922`
3. **Powerchair, how it rides video** — `https://vimeo.com/936455165`

## Local Preview

```bash
cd /workspace/atvpowerchair-site
python3 -m http.server 8080
# Open http://localhost:8080
```

## Deploy to Netlify

### Option A: One-Step Zip / Folder Drag-and-Drop
Upload `/workspace/atvpowerchair-site-deploy.zip` (or drag-and-drop `/workspace/atvpowerchair-site/`) into Netlify Deploys.

### Option B: GitHub + Netlify Continuous Deployment
1. Create a GitHub repository under `Kirk3333` (e.g., `Kirk3333/atvpowerchair`).
2. Push this directory:
   ```bash
   cd /workspace/atvpowerchair-site
   git init
   git add .
   git commit -m "Initial atvpowerchair.com landing page"
   git branch -M main
   git remote add origin https://github.com/Kirk3333/atvpowerchair.git
   git push -u origin main
   ```
3. In Netlify (`kirkinphx` team), select **Add new site → Import an existing project → GitHub**, pick the repo, leave Build command blank, and set Publish directory to `.`.
4. Add custom domain `atvpowerchair.com` / `www.atvpowerchair.com` under Domain Management.
