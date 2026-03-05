# 🚀 Comment mettre HIERA sur GitHub avec les images

## 📋 Prérequis

- ✅ Un compte GitHub (gratuit sur github.com)
- ✅ Git installé sur ton ordinateur (https://git-scm.com/download)
- ✅ Le dossier `hiera-site` avec tous les fichiers

---

## 🎯 Étape 1 : Créer un nouveau repository sur GitHub

1. Va sur https://github.com/new
2. **Remplis les champs :**
   - **Repository name:** `hiera-site` (ou ce que tu veux)
   - **Description:** "Site HIERA - Architecture de la Visibilité"
   - **Public** (pour que ce soit accessible)
3. **Coche:** "Add a README file" (optionnel)
4. **Clique:** "Create repository"

Tu obtiens une URL du type : `https://github.com/tonnom/hiera-site`

---

## 🖥️ Étape 2 : Uploader le dossier complet via GitHub Desktop (PLUS FACILE)

### Option A : GitHub Desktop (RECOMMANDÉ - Plus facile)

1. **Télécharge** GitHub Desktop : https://desktop.github.com/
2. **Lance** l'application
3. **Clique** File → Clone Repository
4. **Colle** l'URL : `https://github.com/tonnom/hiera-site`
5. **Choisis** où sauvegarder le dossier sur ton ordi
6. **Clique** Clone

Ensuite :
7. **Ouvre** l'explorateur de fichiers
8. **Va** au dossier cloné
9. **Copie/colle** dedans TOUT le contenu du dossier `hiera-site` :
   - `index.html`
   - `pages/` (dossier complet)
   - `css/` (dossier complet)
   - `assets/` (dossier complet avec images PNG)
   - `README.md`

10. **Retour à GitHub Desktop**
11. **Tu dois voir** les fichiers dans la colonne de gauche
12. **En bas à gauche**, remplis :
    - **Summary:** "Initial commit - HIERA site with images"
    - **Description:** "Add complete HIERA website with CSS, pages, and images"
13. **Clique** "Commit to main"
14. **Clique** "Push to origin" (en haut à droite)

**✅ C'est uploké !**

---

### Option B : Ligne de commande (terminal)

Si tu préfères le terminal :

```bash
# 1. Va au dossier où tu veux travailler
cd ~/Documents

# 2. Clone le repository
git clone https://github.com/tonnom/hiera-site
cd hiera-site

# 3. Copie tous les fichiers du dossier hiera-site ici
# (utilise l'explorateur pour copier-coller les fichiers)

# 4. Ajoute tous les fichiers
git add .

# 5. Fais un commit
git commit -m "Initial commit - HIERA site with images"

# 6. Envoie sur GitHub
git push origin main
```

---

## ✅ Étape 3 : Activer GitHub Pages

C'est ce qui transforme ton repo en site web !

1. **Va** sur GitHub
2. **Ouvre** ton repository `hiera-site`
3. **Clique** sur "Settings" (en haut à droite)
4. **Dans le menu de gauche**, clique "Pages"
5. **Sous "Source"**, sélectionne **"main"** (ou "master")
6. **Sélectionne le dossier:** `/ (root)`
7. **Clique** "Save"

GitHub va te dire :
> Your site is live at : `https://tonnom.github.io/hiera-site`

**✅ Ton site est en ligne !**

---

## 🖼️ Vérifier que les images s'affichent

1. **Va** sur https://tonnom.github.io/hiera-site
2. **Navigue** entre les pages
3. **Les images doivent apparaître** si le dossier `assets/` contient les fichiers PNG

### Si les images n'apparaissent pas :

**Vérifie que :**
- ✅ Le dossier `assets/` est uploadé sur GitHub
- ✅ Les fichiers PNG sont bien dedans :
  - `modern-building.png`
  - `arcade-structure.png`
  - `escalator-ascension.png`
  - `dome-spiral.png`
- ✅ Les chemins dans le HTML sont corrects : `src="assets/modern-building.png"`

**Pour vérifier la structure :**
1. Va sur ton repository GitHub
2. Clique sur "assets"
3. Tu dois voir les 4 images PNG listées

---

## 🔧 Mettre à jour le site après

Si tu fais des modifications :

### Avec GitHub Desktop :
1. Fais tes modifications dans les fichiers locaux
2. GitHub Desktop les détecte automatiquement
3. En bas à gauche : écris un message (ex: "Update home page")
4. Clique "Commit to main"
5. Clique "Push to origin"
6. **Attends 1-2 minutes** et rafraîchis le site

### Avec le terminal :
```bash
git add .
git commit -m "Description de la modification"
git push origin main
```

---

## 🌐 URL finale de ton site

```
https://tonnom.github.io/hiera-site
```

(Remplace "tonnom" par ton username GitHub)

---

## ⚠️ Problèmes courants

### "Les images ne s'affichent pas"
- Vérifie que `assets/` est bien uploadé
- Rafraîchis le site avec Ctrl+F5 (vide le cache)
- Attends 5 minutes (GitHub peut être lent à mettre à jour)

### "Erreur 404 - Page not found"
- Vérifie que GitHub Pages est activé dans Settings → Pages
- Vérifie que tu as choisi "main" comme source
- Attends quelques minutes le temps que GitHub déploie

### "Le site ne se charge pas"
- Vérifie l'URL : `https://tonnom.github.io/hiera-site` (pas http://)
- Le repository doit être **Public**
- GitHub Pages doit être **activé**

---

## 📋 Checklist finale

- [ ] Repository créé sur GitHub
- [ ] Dossier complet `hiera-site` uploadé (avec `assets/`)
- [ ] Les 4 images PNG dans le dossier `assets/`
- [ ] GitHub Pages activé dans Settings → Pages
- [ ] Source définie sur `main` / `(root)`
- [ ] Site accessible à https://tonnom.github.io/hiera-site
- [ ] Images visibles sur le site en ligne

---

## 🎉 Voilà !

Ton site HIERA est en ligne avec les images ! 🚀

**URL de partage:** https://tonnom.github.io/hiera-site

Tu peux la donner à tes contacts, investisseurs, etc.

---

*Guide GitHub | HIERA*
