# Nexa Labs — Site vitrine

Site vitrine statique (une page) présentant une activité de création d'applications mobiles SaaS et de gestion de flottes mobiles (Mobile Device Management).

## Contenu

- `index.html` — page unique, autonome (HTML/CSS, aucune dépendance à installer).

## Aperçu local

Ouvrir simplement `index.html` dans un navigateur, ou servir le dossier :

```bash
python3 -m http.server 8000
# puis ouvrir http://localhost:8000
```

## Déploiement (Vercel)

Site 100 % statique : aucune configuration nécessaire.

1. Importer ce dépôt GitHub dans Vercel.
2. Laisser les réglages par défaut (aucun build, dossier racine).
3. Déployer — l'URL publique peut ensuite être renseignée sur Stripe.
