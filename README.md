# Maestova

**Des employés IA pour toutes les entreprises.**

Maestova conçoit des « employés IA » — des assistants qui apprennent de chaque validation
humaine et bâtissent une mémoire d'entreprise (un wiki vivant) qui grandit avec l'entreprise.
L'humain reste aux commandes : il approuve, adapte, envoie.

> **Maestova** — l'entreprise (le maître). **Acolyte** — le produit phare (l'employé IA qu'elle forme).

## Ce dépôt

Pour l'instant, ce dépôt héberge la **page d'accueil marketing** d'Acolyte (statique, sans build).

```
maestova/
├── index.html        # landing page (produit : Acolyte)
├── assets/
│   └── styles.css     # styles
├── CNAME              # domaine GitHub Pages (maestova.ai)
└── README.md
```

## Lancer en local

Aucune dépendance. Ouvrez `index.html` dans un navigateur, ou servez le dossier :

```bash
python -m http.server 8000   # puis http://localhost:8000
# ou
npx serve .
```

## Déployer (GitHub Pages — gratuit)

1. Poussez ce dépôt sur GitHub.
2. **Settings → Pages → Source : `main` / root**.
3. Le fichier `CNAME` pointe le site vers **maestova.ai** une fois le domaine acheté et le DNS configuré
   (sinon le site est servi sur `https://<user>.github.io/<repo>/`).

## Marque & domaines

- **Entreprise :** Maestova · **Produit :** Acolyte AI
- **Domaine canonique :** `maestova.ai` (+ `maestova.com` en redirection) — *confirmés disponibles, à acheter.*
- Faire une **recherche de marque** (CIPO + USPTO) sur « Maestova » et « Acolyte » avant impression.
- Version **française** du site obligatoire au Québec (Charte de la langue française / Loi 96) — déjà en français ici.

## Prochaines étapes

Acheter `maestova.ai` + `maestova.com`, faire la recherche de marque, puis brancher
le MVP Acolyte Support sur Gmail. (Feuille de route détaillée tenue à l'interne.)
