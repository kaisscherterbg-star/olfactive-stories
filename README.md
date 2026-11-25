# Olfactive Stories

Site vitrine et boutique de parfums de niche.

- `index.html` : la boutique (page unique, lien direct vers une fiche : `/#p=<nom-du-parfum>`).
- `parfum/<nom-du-parfum>/index.html` : une page par parfum (62), avec sa propre adresse, ses notes, ses prix et son aperçu de partage.
- `og/` : images d'aperçu de partage (WhatsApp, réseaux sociaux), 1200×630.
- `sitemap.xml`, `robots.txt`, `404.html`, `favicon.svg` : référencement et icônes.
- `assets/` : visuels ; `vendor/` et `support.js` : bibliothèques d'exécution.
- Hébergé sur Netlify, déployé automatiquement à chaque mise à jour de la branche `main`. Aucune commande de build : le dossier racine est publié tel quel (voir `netlify.toml`).

Les adresses du sitemap et des aperçus utilisent `https://olfactistories.netlify.app` ; elles sont à régénérer si un nom de domaine personnalisé est branché.

Dernière mise à jour : 25 novembre 2026 (v62).
