# MotionGraphic.si — Vitrine Astro

Landing page statique d'inscription bêta, indépendante de l'application Next.js sur https://studio.motiongraphic.si.

## Développement

```bash
npm install
npm run dev
npm run build
```

## Hostinger (déploiement via Git)
- Répertoire racine : `.`
- Gestionnaire : `npm`
- Commande de compilation : `npm run build`
- Dossier de sortie : `dist`
- Fichier d'entrée Node.js : **laisser vide** (site statique)

La version statique peut aussi être publiée en transférant **le contenu** de `dist/` dans `public_html/`.

Conserver le DNS de `studio.motiongraphic.si` vers XCloud, et vérifier les MX/TXT existants avant toute modification DNS.

## Avant ouverture des inscriptions
Le formulaire est uniquement une démonstration visuelle, il ne stocke aucune adresse. Connecter un backend sécurisé (Edge Function Supabase, contrôles anti-spam, limitation de débit et consentement), puis ajouter mentions légales et politique de confidentialité. Ne pas annoncer d'inscription réussie tant que le backend n'est pas prêt.
