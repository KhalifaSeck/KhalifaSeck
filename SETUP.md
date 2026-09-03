# 🚀 Setup Instructions — KhalifaSeck GitHub Profile

## 1. Create the repository

On GitHub, create a **new public repository** named **exactly** `KhalifaSeck` (same as your username, case-sensitive). This is the magic name GitHub uses to display your profile README on `github.com/KhalifaSeck`.

- ✅ Public
- ✅ Initialize with README
- ❌ Do NOT rename it to `portfolio` — it must be `KhalifaSeck`

## 2. Clone it locally

```bash
git clone https://github.com/KhalifaSeck/KhalifaSeck.git
cd KhalifaSeck
```

## 3. Copy the portfolio content

Copy **everything** from this `portfolio/` folder into your cloned repo:

```
KhalifaSeck/
├── README.md
├── LICENSE
├── SETUP.md              (optional — you can delete this)
├── .github/
│   └── workflows/
│       └── snake.yml
└── assets/
    ├── banner/hero-banner.svg
    ├── sections/divider.svg
    ├── architecture/data-stack-overview.svg
    └── projects/
        ├── gaming-platform-preview.svg
        ├── delivery-lakehouse-preview.svg
        ├── steam-intelligence-preview.svg
        ├── marketing-funnel-preview.svg
        ├── olist-quality-preview.svg
        ├── wolof-asr-preview.svg
        └── ehr-pipeline-preview.svg
```

## 4. Commit and push

```bash
git add .
git commit -m "feat: initial portfolio setup"
git push origin main
```

## 5. Verify

Open **https://github.com/KhalifaSeck** — the README should now display your full portfolio.

## 6. Enable the Snake animation

After the first push, go to your repo → **Actions** tab → enable workflows if prompted.
Then trigger the `Generate Snake` workflow manually **once** (Actions → Generate Snake → Run workflow).
It will create an `output` branch with the animated snake SVG that the README references.

The workflow re-runs automatically every 24 hours.

## 7. Pin your best repositories

On your profile page → **Customize your pins** → select these 6:

1. realtime-gaming-platform
2. realtime-delivery-lakehouse
3. Steam-Intelligence-Platform
4. asr-wolof-speech-recognition
5. EHR-Practice-Fusion-Data-Pipeline
6. marketing-funnel

## 8. Check the repository names match

⚠️ The README links to these exact repo names on your account:

- `realtime-gaming-platform`
- `realtime-delivery-lakehouse`
- `Steam-Intelligence-Platform`
- `videogames-analytics-platform`
- `marketing-funnel`
- `olist-data-quality`
- `asr-wolof-speech-recognition`
- `EHR-Practice-Fusion-Data-Pipeline`
- `Fullstack-Data-Engineering-Project`
- `openfoodfacts-pipeline`
- `IMPLEMENTATION-FROM-SCRATCH-DES-KNN-VOISINS`

If a real repo of yours has a different name, edit `README.md` and update the URL.

## 9. Optional touches

- Update the "Available for work" tag in `hero-banner.svg` if you're not actively looking
- Replace the SVG project previews with real screenshots later (same filename, `.png` instead of `.svg` — then update the extension in `README.md`)
- Add more badges in the "Technical Skills" section as your stack grows

---

**Done!** You now have a professional GitHub portfolio.
