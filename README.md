# ePortfolio — Koffi Aimé Kouassi

Portfolio personnel déployable sur Vercel.

## Structure

```
portfolio/
├── index.html      → page principale
├── style.css       → feuille de style
├── vercel.json     → configuration Vercel
└── README.md       → ce fichier
```

## Déployer sur Vercel

### Option 1 — Via l'interface web (recommandé)

1. Crée un compte sur [vercel.com](https://vercel.com) (gratuit)
2. Crée un dépôt GitHub avec ces fichiers :
   - Va sur [github.com](https://github.com) → **New repository**
   - Uploade les fichiers `index.html`, `style.css`, `vercel.json`
3. Sur Vercel → **Add New Project** → importe ton dépôt GitHub
4. Clique **Deploy** — c'est tout ✅

### Option 2 — Via Vercel CLI

```bash
npm install -g vercel
cd portfolio/
vercel
```

Suis les instructions dans le terminal. Ton site sera en ligne en moins d'une minute.

## Notes

- Les images sont hébergées sur Imgur (liens externes) — aucun fichier image à gérer.
- La police Inter est chargée depuis Google Fonts.
- Le site est 100% statique : HTML + CSS, aucun serveur requis.
