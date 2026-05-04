# Thierry Domballe — Hypnose & Coaching — V8 Final

## Fichiers à uploader sur GitHub (TOUS les 5)
- index.html     ← Site complet, photo en fichier séparé
- photo.jpg      ← Photo de profil (NOUVEAU - fichier séparé)
- success.html   ← Page confirmation formulaire
- netlify.toml   ← Config Netlify
- README.md      ← Ce fichier

## Pourquoi ce changement ?
La photo était encodée en base64 directement dans index.html.
Ce fichier trop volumineux empêchait Netlify de scanner
et détecter le formulaire data-netlify="true".
En séparant la photo, Netlify peut maintenant parser
correctement le formulaire.

## Config Netlify formulaire (1 fois)
Site configuration > Forms > Form notifications
> Add notification > Email > contact@thierry-domballe.fr

## Contact
- Email : contact@thierry-domballe.fr
- Tél : 07 60 50 72 51
