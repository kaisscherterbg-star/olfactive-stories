# Olfactive Stories

Site vitrine et boutique de parfums de niche.

- `index.html` : la boutique (page unique). Ouvrir une fiche affiche l'adresse `/parfum/<nom-du-parfum>/` (retour arrière géré) ; le lien direct `/#p=<nom-du-parfum>` ouvre aussi la fiche.
- `parfum/<nom-du-parfum>/index.html` : une page par parfum (64), avec sa propre adresse, ses notes, ses prix et son aperçu de partage.
- `og/` : images d'aperçu de partage (WhatsApp, réseaux sociaux), 1200×630.
- `sitemap.xml`, `robots.txt`, `404.html`, `favicon.svg` : référencement et icônes.
- `assets/` : visuels ; `vendor/` et `support.js` : bibliothèques d'exécution.
- Hébergé sur Cloudflare (Workers, fichiers statiques), déployé automatiquement à chaque mise à jour de la branche `main`. Aucune commande de build : le dossier racine est publié tel quel (voir `wrangler.jsonc`, `.assetsignore` et `_headers`). `netlify.toml` est conservé pour mémoire (ancien hébergement).

Adresse du site : `https://olfactive-stories.fr`. Le sitemap, les images d'aperçu et les pages utilisent cette adresse ; en cas de changement de domaine, régénérer le site avec la nouvelle adresse.

Dernière mise à jour : 27 novembre 2026 (v62.4).
