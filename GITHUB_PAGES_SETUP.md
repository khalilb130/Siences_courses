# 🚀 Guide d'activation GitHub Pages

## Étapes pour activer votre site web

### 1. Vérifier que vos fichiers sont bien push sur GitHub

```bash
git add .
git commit -m "Ajout des cartes mentales interactives"
git push origin main
```

*(ou `master` selon le nom de votre branche principale)*

### 2. Activer GitHub Pages

1. Allez sur votre dépôt GitHub : `https://github.com/votre-username/Siences_courses`

2. Cliquez sur **Settings** (⚙️ Paramètres)

3. Dans le menu de gauche, cliquez sur **Pages**

4. Sous **Source**, sélectionnez :
   - **Branch:** `main` (ou `master`)
   - **Folder:** `/ (root)`

5. Cliquez sur **Save**

6. Attendez quelques minutes (généralement 1-5 minutes)

7. Rafraîchissez la page

8. Votre site sera accessible à : `https://votre-username.github.io/Siences_courses/`

### 3. Accéder aux différentes pages

Une fois activé, vous pourrez accéder à :

- **Page d'accueil :** `https://votre-username.github.io/Siences_courses/`
- **Index Maths :** `https://votre-username.github.io/Siences_courses/Math/`
- **Produit Scalaire :** `https://votre-username.github.io/Siences_courses/Math/premiere/produit_scalaire/carte_mentale_produit_scalaire.html`
- **Suites :** `https://votre-username.github.io/Siences_courses/Math/premiere/suite_arithmeco_geo/carte_mentale_suites_arithmetico_geometriques.html`

### 4. Mettre à jour le README

Dans le fichier `README.md`, remplacez `votre-username` par votre véritable nom d'utilisateur GitHub.

### 5. Partager votre site

Une fois en ligne, vous pouvez partager directement les liens avec vos étudiants !

## 🔧 Résolution de problèmes

### Le site ne s'affiche pas ?
- Attendez 5-10 minutes après l'activation
- Vérifiez que la branche et le dossier sont corrects dans les paramètres
- Assurez-vous que `index.html` est bien à la racine

### Les liens ne fonctionnent pas ?
- Vérifiez que tous les fichiers sont bien push
- Vérifiez les chemins relatifs dans les liens HTML

### Erreur 404 ?
- Vérifiez l'orthographe des noms de fichiers (respecte la casse)
- Assurez-vous que la structure des dossiers est correcte

## 📱 Tester localement avant de push

Ouvrez simplement `index.html` dans votre navigateur pour tester en local !

## ✅ Checklist avant activation

- [ ] Tous les fichiers HTML sont créés
- [ ] Les chemins relatifs sont corrects
- [ ] Les fichiers sont push sur GitHub
- [ ] Le dépôt est public (obligatoire pour GitHub Pages gratuit)

**Bonne chance ! 🎉**
