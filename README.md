# Thierry Domballe — Hypnose & Coaching

Site vitrine professionnel — Version 7

## Structure du projet

```
thierry-domballe-site/
├── index.html        ← Site complet (HTML/CSS/JS en un seul fichier)
├── netlify.toml      ← Configuration Netlify
└── README.md         ← Ce fichier
```

## Déploiement sur Netlify

### Option A — Drag & Drop (la plus simple)
1. Aller sur [netlify.com](https://netlify.com)
2. Se connecter ou créer un compte gratuit
3. Glisser-déposer le dossier `thierry-domballe-site` dans la zone de dépôt
4. Le site est en ligne en 30 secondes

### Option B — Via GitHub (recommandé pour les mises à jour)
1. Créer un compte sur [github.com](https://github.com)
2. Créer un nouveau repository nommé `thierry-domballe-site`
3. Uploader les 3 fichiers (index.html, netlify.toml, README.md)
4. Sur Netlify : "New site from Git" → connecter GitHub → choisir le repo
5. Netlify détecte automatiquement la config et déploie

### Mettre à jour le site après modification
1. Modifier `index.html` localement
2. Sur GitHub : remplacer le fichier (bouton "Upload files")
3. Netlify redéploie automatiquement en 1-2 minutes

## Connecter votre nom de domaine
1. Acheter `thierrydomballe.fr` sur OVH ou Gandi
2. Dans Netlify : "Domain settings" → "Add custom domain"
3. Suivre les instructions pour pointer les DNS vers Netlify

## À compléter avant la mise en ligne
- [ ] Remplacer `contact@thierrydomballe.fr` par votre vraie adresse
- [ ] Remplacer `+33 6 XX XX XX XX` par votre vrai numéro
- [ ] Ajouter les témoignages clients quand disponibles
- [ ] Activer la description EMDR après certification
- [ ] Créer la fiche Google Business Profile
