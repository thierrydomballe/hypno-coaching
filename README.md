# Thierry Domballe — Hypnose & Coaching — V8 Fix

## Fichiers à uploader sur GitHub
- index.html  ← Site complet avec formulaire corrigé + photo
- success.html ← Page de confirmation après envoi du formulaire
- netlify.toml ← Config Netlify
- README.md

## Corrections V8 Fix
- Formulaire : action="/success.html" ajouté → résout l'erreur 404
- data-netlify="true" + honeypot anti-spam conservés
- Photo de profil restaurée (base64 intégré)
- Email contact@thierry-domballe.fr : word-break ajouté (plus de coupure)
- Téléphone : 07 60 50 72 51

## Étapes GitHub → Netlify
1. Uploader index.html (remplace l'existant)
2. Uploader success.html (NOUVEAU fichier à créer)
3. netlify.toml si modifié
4. Netlify redéploie en 1-2 min

## Config Netlify formulaire (1 fois)
Site configuration > Forms > Form notifications
> Add notification > Email > contact@thierry-domballe.fr
