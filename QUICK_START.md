# 🚀 Guide de démarrage rapide - V2.0

## 🆕 Nouveautés Version 2.0

### ⭐ Features principales
- **Toggle Mode Clair/Sombre** (bouton en haut à droite)
- **12 nouveaux éléments IA Générative** (Text-to-Video, Image-to-Image, etc.)
- **114 éléments au total** (+7 depuis V1.0)
- **Contact direct** dans le footer (email + LinkedIn)
- **Responsive amélioré** pour mobile

---

## Structure du projet

```
tableau-periodique-ia/
├── index.html              # 🌐 Fichier principal à ouvrir (V2)
├── README.md              # 📖 Documentation complète
├── LICENSE                # ⚖️ Licence CC BY-SA 4.0
├── CHANGELOG.md          # 📝 Historique des versions (V2.0)
├── QUICK_START.md        # 🚀 Ce fichier
├── .gitignore            # 🚫 Fichiers à ignorer par Git
└── docs/
    ├── ELEMENTS.md       # 📚 Liste des 114 éléments
    └── CONTRIBUTING.md   # 🤝 Guide de contribution
```

---

## ⚡ Démarrage rapide

### Option 1 : Ouverture locale
```bash
# Double-cliquez sur index.html
# OU
open index.html
```

### Option 2 : Hébergement local
```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js
npx http-server

# Accédez à http://localhost:8000
```

### Option 3 : GitHub Pages
```bash
# 1. Créez un repo sur GitHub
git init
git add .
git commit -m "Version 2.0: Mode clair/sombre + 12 nouveaux éléments IA Générative"
git branch -M main
git remote add origin https://github.com/VOTRE-USERNAME/tableau-periodique-ia.git
git push -u origin main

# 2. Activez GitHub Pages dans Settings > Pages
# 3. Votre site sera accessible à :
# https://VOTRE-USERNAME.github.io/tableau-periodique-ia/
```

---

## 🎨 Utilisation du Mode Clair/Sombre

### Toggle entre les modes
1. **Cliquez** sur le bouton en haut à droite
2. **Mode Clair** ☀️ (par défaut) : Fond blanc, texte noir
3. **Mode Sombre** 🌙 : Fond bleu foncé, texte blanc
4. La transition est **instantanée** avec animation fluide

### Raccourci clavier (à venir V2.1)
- `Ctrl + Shift + D` pour toggle le mode

---

## 🆕 Explorer les nouveaux éléments IA Générative

Les éléments **51 à 62** sont nouveaux dans la V2.0 :

### Text-to-X (Génération à partir de texte)
- **#51 T2i** : Text-to-Image (DALL-E, Midjourney)
- **#52 T2v** : Text-to-Video (Sora, Runway)
- **#53 T2a** : Text-to-Audio (MusicGen)
- **#54 T23** : Text-to-3D (DreamFusion)

### Transformations
- **#55 I2i** : Image-to-Image (Style transfer)
- **#56 I2v** : Image-to-Video (Pika)
- **#57 V2v** : Video-to-Video (Deepfake)
- **#58 A2a** : Audio-to-Audio (Voice cloning)

### Applications spécialisées
- **#59 T2c** : Text-to-Code (GitHub Copilot)
- **#60 Inp** : Inpainting (Photoshop Generative Fill)
- **#61 Out** : Outpainting (DALL-E)
- **#62 Upc** : Upscaling (Topaz Gigapixel)

**Cliquez** sur chaque élément pour voir sa définition complète !

---

## 📝 Checklist avant publication GitHub

Avant de publier la V2.0 sur GitHub :

- [ ] Remplacez `votre-username` par votre nom d'utilisateur GitHub dans :
  - `README.md` (tous les liens)
  - Ce fichier
  
- [ ] Vérifiez les informations de contact dans `index.html` :
  - ✉️ Email : sayhi@naullynicolas.ch
  - 💼 LinkedIn : linkedin.com/in/naullynicolas
  
- [ ] Ajoutez une capture d'écran `preview.png` à la racine
  - Dimension recommandée : 1920×1080px
  - Format : PNG
  - **Montrez les 2 modes** (clair et sombre)
  
- [ ] Testez le fichier `index.html` sur :
  - [ ] Chrome (mode clair + sombre)
  - [ ] Firefox (mode clair + sombre)
  - [ ] Safari (mode clair + sombre)
  - [ ] Mobile iOS (mode clair + sombre)
  - [ ] Mobile Android (mode clair + sombre)

- [ ] Vérifiez le responsive :
  - [ ] Desktop (>1400px)
  - [ ] Laptop (1200-1400px)
  - [ ] Tablette (800-1200px)
  - [ ] Mobile portrait (450-800px)
  - [ ] Petit mobile (<450px)

---

## 🎨 Personnalisation rapide

### Modifier les couleurs
Dans `index.html`, section `<style>`, variables CSS :

```css
:root {
    /* Mode Clair */
    --bg-primary: linear-gradient(135deg, #f0f4f8 0%, #e2e8f0 100%);
    --text-primary: #1a202c;
    /* ... */
}

body.dark-mode {
    /* Mode Sombre */
    --bg-primary: linear-gradient(135deg, #0f0f23 0%, #1a1a2e 100%);
    --text-primary: #ffffff;
    /* ... */
}
```

### Ajouter un élément
Dans `index.html`, section `<script>`, array `elements` :

```javascript
{ 
    number: 115, 
    symbol: "New", 
    name: "Nouvel Élément", 
    category: "generative", 
    description: "Description détaillée ici" 
}
```

### Modifier le mode par défaut
Dans `index.html`, ajoutez la classe `dark-mode` au `<body>` :

```html
<body class="dark-mode">  <!-- Mode sombre par défaut -->
<!-- OU -->
<body>                    <!-- Mode clair par défaut -->
```

---

## 🔗 Liens utiles

- **Documentation complète** : `README.md`
- **Liste des 114 éléments** : `docs/ELEMENTS.md`
- **Historique des versions** : `CHANGELOG.md`
- **Guide de contribution** : `docs/CONTRIBUTING.md`
- **Licence** : `LICENSE`

---

## 🆘 Problèmes courants

### Le mode clair/sombre ne fonctionne pas
- Vérifiez que JavaScript est activé dans votre navigateur
- Ouvrez la console (F12) pour voir les erreurs
- Testez dans un autre navigateur

### Le tableau ne s'affiche pas
- Vérifiez que JavaScript est activé
- Ouvrez la console (F12) pour voir les erreurs
- Assurez-vous d'ouvrir `index.html`, pas un autre fichier
- Testez dans un autre navigateur (Chrome recommandé)

### Les éléments sont mal alignés
- Vérifiez la taille de votre écran
- Le design est responsive : testez différentes résolutions
- Zoomez/dézoomez (Ctrl +/-)
- Sur mobile, essayez en mode portrait et paysage

### Les nouveaux éléments (51-62) ne s'affichent pas
- Assurez-vous d'utiliser la **version 2.0** du fichier `index.html`
- Vérifiez que tous les 114 éléments sont dans le code JavaScript
- Rafraîchissez la page (Ctrl + F5)

### Le modal ne s'ouvre pas
- Vérifiez JavaScript dans la console (F12)
- Testez sur un autre navigateur
- Essayez un clic droit puis "Voir les détails"

---

## 📊 Prochaines étapes

1. **Testez localement** le fichier `index.html` V2.0
2. **Testez les 2 modes** (clair et sombre)
3. **Explorez les nouveaux éléments** (51-62)
4. **Personnalisez** le README avec vos infos
5. **Ajoutez** une capture d'écran `preview.png` (2 modes)
6. **Créez** un repository GitHub
7. **Publiez** sur GitHub Pages
8. **Partagez** votre projet !

---

## 💡 Idées d'amélioration pour V2.1+

### Fonctionnalités à venir
- [ ] Barre de recherche d'éléments
- [ ] Filtrage interactif par catégorie
- [ ] Export en image (PNG/SVG)
- [ ] Mode impression optimisé
- [ ] Raccourcis clavier
- [ ] Traductions (EN, ES, DE)
- [ ] Accessibilité WCAG 2.1 AA

### Améliorations design
- [ ] Animation d'entrée des éléments
- [ ] Transition entre périodes
- [ ] Visualisation des relations
- [ ] Mode présentation (plein écran)

### Contenu
- [ ] Quiz interactif
- [ ] Timeline historique de l'IA
- [ ] Liens vers ressources externes
- [ ] Exemples d'utilisation

---

## 📞 Contact & Support

Pour toute question sur la V2.0 :

- ✉️ **Email** : sayhi@naullynicolas.ch
- 💼 **LinkedIn** : [linkedin.com/in/naullynicolas](https://www.linkedin.com/in/naullynicolas/)
- 🐛 **Issues GitHub** : Ouvrez une issue
- 💬 **Discussions** : Utilisez les GitHub Discussions

---

## 📈 Comparaison V1.0 vs V2.0

| Feature | V1.0 | V2.0 |
|---------|------|------|
| **Éléments** | 107 | 114 ✅ |
| **Mode clair** | ❌ | ✅ |
| **Mode sombre** | ✅ | ✅ |
| **Toggle thème** | ❌ | ✅ |
| **Contact footer** | ❌ | ✅ |
| **IA Générative** | 12 | 24 ✅ |
| **Text-to-Video** | ❌ | ✅ |
| **Text-to-3D** | ❌ | ✅ |
| **Upscaling** | ❌ | ✅ |

---

**Bon développement avec la V2.0 ! 🚀**

Version 2.0 - 2026 | Naully Nicolas

[⬆ Retour en haut](#-guide-de-démarrage-rapide---v20)
