# NKS &amp; AUDIA Consulting Partnership Hub

Shared, co-branded materials for the Strategic Church Referral Partnership between **Neighborhood Kids Schools (NKS)** and **AUDIA Consulting**.

## What is here

| Document | Path | Description |
|---|---|---|
| Landing page | `index.html` | Co-branded hub that links to every document below. |
| Memorandum of Understanding | `mou/index.html` | The signed referral partnership agreement (effective May 27, 2026). |
| Target Church Discovery Call agenda | `discovery-agenda/index.html` | Discovery agenda to define the golden-example church profile (June 15, 2026). |
| Shared assets | `assets/` | Logos and favicon used across all pages. |

## Structure

```
nks-audia-partnership/
├── index.html              Landing page (links to all documents)
├── README.md
├── assets/                 Shared logos and favicon
│   ├── audia-horizontal-full-color.svg
│   ├── neighborhood-kids-schools-logo-wide.png
│   └── favicon-on-green-32x32.png
├── mou/
│   └── index.html          Memorandum of Understanding
└── discovery-agenda/
    └── index.html          Target Church Discovery Call agenda
```

## Publishing with GitHub Pages

1. Create a new repository and upload the **contents** of this folder to the repository root.
2. In the repository, go to **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, then save.
4. After a minute, the hub will be live at `https://<your-username>.github.io/<repo-name>/`.

The landing page links to each document with relative paths, so everything works once the folder is uploaded as-is.

## Adding new documents

Place each new document in its own subfolder with an `index.html` (for example `meeting-report/index.html`), reference shared images with `../assets/...`, then add a matching card to `index.html` on the landing page.

---

&copy; 2026 AUDIA Consulting and Neighborhood Kids Schools.
