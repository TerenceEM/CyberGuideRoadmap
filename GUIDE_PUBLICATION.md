# Guide de Publication du Site CyberGuide

## Fichiers créés

Le site complet est prêt avec les fichiers suivants :
- `index.html` - Page d'accueil
- `secteurs.html` - Contextes et secteurs d'activité (6 secteurs)
- `sensibilisation.html` - Sensibilisation par profil (3 profils)
- `reglementation.html` - Réglementations et normes
- `acteurs.html` - Acteurs étatiques (6+ acteurs)
- `prestataires.html` - Prestataires cybersécurité (6 catégories)
- `outils.html` - Outils de sécurité (8 catégories avec 3-6 outils chacune)
- `action.html` - Quiz, checklists et scénario
- `style.css` - Feuille de style complète

## Options de Publication (Gratuites)

### Option 1 : GitHub Pages (Recommandé - Simple et Gratuit)

1. **Créer un compte GitHub** (si vous n'en avez pas) : https://github.com
2. **Créer un nouveau repository** :
   - Cliquer sur "New repository"
   - Nom : `cyberguide` (ou autre nom de votre choix)
   - Cocher "Public"
   - Cliquer "Create repository"

3. **Upload des fichiers** :
   - Cliquer sur "uploading an existing file"
   - Glisser-déposer tous les fichiers HTML et le CSS
   - Commit : "Initial commit"

4. **Activer GitHub Pages** :
   - Aller dans Settings > Pages
   - Source : "Deploy from a branch"
   - Branch : main / root
   - Sauvegarder

5. **Votre site sera disponible à** : `https://[votre-username].github.io/cyberguide/`

### Option 2 : Netlify (Drag & Drop)

1. **Aller sur** : https://www.netlify.com/
2. **Créer un compte gratuit**
3. **"Add new site" > "Deploy manually"**
4. **Glisser-déposer le dossier contenant tous vos fichiers**
5. **Le site est publié immédiatement** avec une URL comme `https://random-name-123.netlify.app`
6. **Personnaliser l'URL** : Site settings > Change site name

### Option 3 : Vercel

1. **Aller sur** : https://vercel.com
2. **Sign up avec GitHub**
3. **Import project**
4. **Sélectionner le repository GitHub** (si option 1 faite)
5. **Deploy** (automatique)
6. **URL fournie** : `https://[project-name].vercel.app`

### Option 4 : Cloudflare Pages

1. **Aller sur** : https://pages.cloudflare.com/
2. **Sign up / Log in**
3. **"Create a project"**
4. **"Direct Upload"**
5. **Upload tous les fichiers**
6. **Deploy** - URL : `https://[project-name].pages.dev`

### Option 5 : Render (Static Site)

1. **Aller sur** : https://render.com
2. **Sign up gratuit**
3. **"New Static Site"**
4. **Connect repository** (GitHub) ou "Deploy from repository"
5. **Build & Deploy**

## Recommandation

**GitHub Pages** est la solution la plus simple et la plus fiable :
- ✅ Gratuit
- ✅ Aucune limite de temps
- ✅ Facile à mettre à jour (juste commit les nouveaux fichiers)
- ✅ URL propre et professionnelle
- ✅ Pas besoin de carte bancaire

## Après la publication

1. **Tester le site** : Vérifier que toutes les pages fonctionnent
2. **Copier l'URL complète** pour le rapport PDF
3. **Prendre des captures d'écran** de chaque page pour le rapport

## Mise à jour du site

Si vous utilisez GitHub Pages :
1. Modifier les fichiers localement
2. Commit et push vers GitHub
3. Le site se met à jour automatiquement

## Support

En cas de problème :
- GitHub Pages : https://docs.github.com/pages
- Netlify : https://docs.netlify.com/
- Vercel : https://vercel.com/docs