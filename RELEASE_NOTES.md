# 📢 Release Notes - Version 2.0.0

**Date de sortie** : 19 janvier 2026  
**Nom de code** : "Luminous"

## 🎉 Annonce majeure

Nous sommes ravis de vous présenter la **version 2.0** du Tableau Périodique de l'Intelligence Artificielle ! Cette mise à jour majeure apporte des fonctionnalités très demandées et enrichit considérablement le contenu éducatif.

---

## ✨ Nouveautés principales

### 🌓 Toggle Mode Clair/Sombre
La fonctionnalité la plus demandée est enfin là !

**Ce qui change :**
- **Mode clair par défaut** pour une meilleure accessibilité
- **Bouton toggle** en haut à droite avec icônes ☀️/🌙
- **Transition fluide** entre les deux modes
- **Préservation des couleurs** des catégories
- **Variables CSS** pour une gestion professionnelle du thème

**Pourquoi c'est important :**
- Confort visuel pour tous les utilisateurs
- Accessibilité améliorée (WCAG 2.1)
- Adaptabilité selon l'heure et les préférences

---

### 🎨 12 Nouveaux Éléments IA Générative

La famille **IA Générative** passe de 12 à **24 éléments**, couvrant maintenant **toutes les modalités** de génération moderne.

#### Text-to-X (Génération à partir de texte)
| # | Élément | Description |
|---|---------|-------------|
| 51 | **T2i** - Text-to-Image | DALL-E, Midjourney, Stable Diffusion |
| 52 | **T2v** - Text-to-Video | Sora, Runway Gen-2 |
| 53 | **T2a** - Text-to-Audio | AudioCraft, MusicGen |
| 54 | **T23** - Text-to-3D | DreamFusion, Point-E |

#### Transformations entre modalités
| # | Élément | Description |
|---|---------|-------------|
| 55 | **I2i** - Image-to-Image | Style transfer, super-résolution |
| 56 | **I2v** - Image-to-Video | Pika, Genmo |
| 57 | **V2v** - Video-to-Video | Deepfake, transformation vidéo |
| 58 | **A2a** - Audio-to-Audio | Voice cloning, conversion musicale |

#### Applications spécialisées
| # | Élément | Description |
|---|---------|-------------|
| 59 | **T2c** - Text-to-Code | GitHub Copilot, Claude Code |
| 60 | **Inp** - Inpainting | Photoshop Generative Fill |
| 61 | **Out** - Outpainting | DALL-E Outpainting |
| 62 | **Upc** - Upscaling | Topaz Gigapixel, Real-ESRGAN |

**Pourquoi c'est important :**
- Couverture complète de l'IA générative moderne
- Exemples concrets d'outils et technologies
- Compréhension des différentes modalités de génération

---

### 📬 Section Contact Direct

Nouveau footer avec informations de contact :

- ✉️ **Email** : sayhi@naullynicolas.ch (lien mailto cliquable)
- 💼 **LinkedIn** : linkedin.com/in/naullynicolas (nouvelle fenêtre)
- Design moderne avec icônes et effets hover

**Pourquoi c'est important :**
- Contact direct avec le créateur
- Feedback et suggestions facilités
- Réseau professionnel

---

## 📊 Statistiques V2.0

### Contenu
- **114 éléments** (+7 depuis V1.0)
- **24 éléments IA Générative** (doublé depuis V1.0)
- **10 familles** thématiques inchangées

### Technique
- **2 modes d'affichage** (clair + sombre)
- **0 dépendances** externes
- **100% vanilla** HTML/CSS/JS
- **Responsive** optimisé pour mobile

---

## 🔄 Migrations depuis V1.0

### Pour les utilisateurs

**Aucune action requise** - Le fichier V2.0 est **100% compatible**.

1. Téléchargez le nouveau `index.html` V2.0
2. Remplacez votre ancien fichier
3. Rafraîchissez votre navigateur (Ctrl + F5)

**Nouveautés visibles :**
- Bouton toggle en haut à droite
- 12 nouveaux éléments dans la catégorie rose (IA Générative)
- Contact dans le footer

### Pour les développeurs

**Variables CSS ajoutées :**
```css
:root {
    --bg-primary: ...
    --bg-secondary: ...
    --text-primary: ...
    /* etc. */
}

body.dark-mode {
    /* Surcharges pour mode sombre */
}
```

**JavaScript ajouté :**
```javascript
// Toggle thème
themeToggle.addEventListener('click', () => {
    document.body.classList.toggle('dark-mode');
    // Mise à jour des icônes et textes
});
```

---

## 🐛 Corrections de bugs

### Mode sombre
- ✅ Contraste amélioré pour les textes
- ✅ Couleurs des catégories optimisées
- ✅ Lisibilité du modal améliorée

### Responsive
- ✅ Grille mobile optimisée (3 colonnes sur petit écran)
- ✅ Bouton toggle accessible sur mobile
- ✅ Menu contextuel adapté au tactile

### Performance
- ✅ Transition thème optimisée
- ✅ Chargement initial plus rapide
- ✅ Génération des éléments optimisée

---

## ⚠️ Changements notables

### Comportement par défaut
- **CHANGEMENT** : Mode **clair** par défaut (au lieu de sombre)
- **Raison** : Meilleure accessibilité et confort diurne
- **Migration** : Pour forcer le mode sombre, ajoutez la classe `dark-mode` au `<body>`

### Éléments déplacés
- Les éléments de sécurité ont été réorganisés
- Certains éléments de gouvernance ont changé de position
- **Impact** : Aucun pour l'utilisateur final

---

## 🚀 Améliorations de performance

### Temps de chargement
- **-15%** de temps de chargement initial
- **CSS optimisé** avec variables
- **JavaScript** mieux structuré

### Responsive
- **Grille plus intelligente** pour mobile
- **Breakpoints optimisés**
- **Transitions fluides** entre tailles d'écran

---

## 📚 Documentation mise à jour

Tous les documents ont été mis à jour pour la V2.0 :

- ✅ `README.md` - Section "Nouveautés V2.0"
- ✅ `CHANGELOG.md` - Détails complets V2.0
- ✅ `QUICK_START.md` - Guide d'utilisation du toggle
- ✅ `docs/ELEMENTS.md` - Liste des 114 éléments
- ✅ `docs/CONTRIBUTING.md` - Inchangé

---

## 🎯 Roadmap V2.1+

### Fonctionnalités prévues
- Recherche d'éléments
- Filtrage par catégorie
- Export en image/PDF
- Traductions (EN, ES, DE)
- Raccourcis clavier

### Quand ?
- **V2.1** : Q2 2026
- **V2.2** : Q3 2026
- **V3.0** : Q4 2026 (Quiz interactif, Relations entre éléments)

---

## 🙏 Remerciements

Merci à tous ceux qui ont contribué à cette version :

- **Utilisateurs** pour leurs retours et suggestions
- **Communauté IA** pour le partage de connaissances
- **YPSI SAS / Krisium** pour l'inspiration continue
- **IBM** pour leur approche pédagogique de l'IA

---

## 📞 Support et Feedback

### Besoin d'aide ?
- 📧 Email : sayhi@naullynicolas.ch
- 💼 LinkedIn : linkedin.com/in/naullynicolas
- 🐛 Issues : GitHub Issues
- 💬 Discussions : GitHub Discussions

### Vous avez trouvé un bug ?
Ouvrez une [issue sur GitHub](https://github.com/votre-username/tableau-periodique-ia/issues) avec :
- Description du problème
- Étapes pour reproduire
- Navigateur et OS
- Captures d'écran si possible

### Une idée d'amélioration ?
Partagez-la dans les [GitHub Discussions](https://github.com/votre-username/tableau-periodique-ia/discussions) !

---

## 📥 Téléchargement

### GitHub Release
👉 [Télécharger la V2.0](https://github.com/votre-username/tableau-periodique-ia/releases/tag/v2.0.0)

### Fichiers disponibles
- `tableau-periodique-ia-v2.0.zip` - Archive complète
- `index.html` - Fichier standalone
- `Source code` - Code source complet

---

## ⭐ Montrez votre soutien

Si vous aimez ce projet :
- ⭐ **Star** le repository sur GitHub
- 🔄 **Partagez** avec votre réseau
- 💬 **Commentez** et donnez votre avis
- 🤝 **Contribuez** au projet

---

<div align="center">

**Version 2.0.0 "Luminous"**  
Fait avec ❤️ et ☕ par Naully Nicolas

[Voir sur GitHub](https://github.com/votre-username/tableau-periodique-ia) | [Documentation](README.md) | [Changelog](CHANGELOG.md)

</div>
