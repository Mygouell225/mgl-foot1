# MGL FOOT - Communauté Gaming Football

## 🚀 Déploiement sur Vercel

Pour déployer ce projet sur Vercel, suivez ces étapes :

1. **Créer un compte sur Vercel**
   - Si vous n'avez pas encore de compte, créez-en un sur [vercel.com](https://vercel.com)
   - Vous pouvez vous connecter avec GitHub, GitLab ou Bitbucket

2. **Connecter votre projet**
   - Allez sur [vercel.com/new](https://vercel.com/new)
   - Connectez votre dépôt GitHub
   - Sélectionnez votre dépôt MGL FOOT

3. **Configuration du déploiement**
   - Vercel détectera automatiquement que c'est un projet Next.js
   - Assurez-vous que les paramètres suivants sont corrects :
     - Build Command: `npm run build`
     - Output Directory: `out`
     - Development Command: `npm run dev`

4. **Variables d'environnement**
   - Dans le tableau de bord Vercel, allez dans Settings > Environment Variables
   - Ajoutez les variables suivantes :
     - `NEXT_PUBLIC_SITE_URL`: URL de votre site Vercel
     - `NEXT_PUBLIC_API_URL`: URL de votre API Vercel

5. **Déploiement**
   - Une fois tout configuré, Vercel déplacera automatiquement votre site
   - Vous recevrez une URL de déploiement préfixée par `mgl-foot.vercel.app`

## 🛠️ Structure du projet

```
src/
├── app/           # Pages Next.js
├── components/    # Composants réutilisables
└── lib/           # Fonctionnalités utilitaires
```

## 📦 Technologies utilisées

- Next.js 14
- Tailwind CSS
- Framer Motion
- Next-themes
- React

## 📝 Notes importantes

- Le site est configuré pour utiliser le thème sombre par défaut
- Les images sont optimisées avec Next.js Image
- Le site est optimisé pour le SEO
- Le dark mode est activé par défaut
