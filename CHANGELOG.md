# Changelog

Toutes les modifications notables de ce projet seront documentées dans ce fichier.

Le format est basé sur [Keep a Changelog](https://keepachangelog.com/fr/1.0.0/),
et ce projet adhère au [Semantic Versioning](https://semver.org/lang/fr/).

## [2.0.0] - 2026-01-19

### 🎉 Version majeure avec nouvelles fonctionnalités

#### Ajouté
- **Toggle Mode Clair/Sombre** 🌓
  - Mode clair par défaut pour meilleure accessibilité
  - Mode sombre disponible via bouton en haut à droite
  - Icônes ☀️ (clair) et 🌙 (sombre)
  - Transition fluide entre les modes
  - Variables CSS pour gestion complète du thème
  - Préservation des couleurs de catégories dans les deux modes

- **12 Nouveaux Éléments IA Générative** 🎨
  - #51 **T2i - Text-to-Image** : DALL-E, Midjourney, Stable Diffusion
  - #52 **T2v - Text-to-Video** : Sora, Runway Gen-2
  - #53 **T2a - Text-to-Audio** : AudioCraft, MusicGen
  - #54 **T23 - Text-to-3D** : DreamFusion, Point-E
  - #55 **I2i - Image-to-Image** : Style transfer, super-résolution
  - #56 **I2v - Image-to-Video** : Pika, Genmo
  - #57 **V2v - Video-to-Video** : Deepfake, transformation vidéo
  - #58 **A2a - Audio-to-Audio** : Voice cloning, conversion musicale
  - #59 **T2c - Text-to-Code** : GitHub Copilot, Claude Code
  - #60 **Inp - Inpainting** : Photoshop Generative Fill
  - #61 **Out - Outpainting** : DALL-E Outpainting
  - #62 **Upc - Upscaling** : Topaz Gigapixel, Real-ESRGAN

- **Section Contact** 📬
  - Email cliquable : sayhi@naullynicolas.ch
  - Lien LinkedIn : linkedin.com/in/naullynicolas
  - Design moderne avec icônes ✉️ et 💼
  - Effets hover avec transition

- **Inspirations enrichies**
  - Référence au Tableau Périodique de l'IA d'IBM
  - Lien vers la vidéo YouTube explicative

#### Modifié
- **Passage de 107 à 114 éléments** (+7 éléments)
- **Catégorie IA Générative** : passage de 12 à 24 éléments (doublé)
- **Responsive amélioré** pour mobile avec grille 3 colonnes
- **Positionnement** des éléments ajusté pour inclure les nouveaux
- **Footer** redesigné avec section contact dédiée

#### Design
- **Mode Clair** (nouveau défaut) :
  - Fond : gradient blanc/gris clair (#f0f4f8 → #e2e8f0)
  - Texte : noir/gris foncé (#1a202c)
  - Éléments : fond blanc semi-transparent
  
- **Mode Sombre** (conservé) :
  - Fond : gradient bleu foncé (#0f0f23 → #1a1a2e)
  - Texte : blanc/gris clair (#ffffff)
  - Éléments : fond sombre semi-transparent

#### Documentation
- README.md mis à jour avec section "Nouveautés V2.0"
- CHANGELOG.md avec détails de la version 2.0
- Liste des 114 éléments dans ELEMENTS.md
- Statistiques mises à jour

---

## [1.0.0] - 2026-01-19

### 🎉 Version initiale

#### Ajouté
- **107 éléments** couvrant l'ensemble de l'écosystème IA
- **10 familles thématiques** avec code couleur
  - Architecture & Fondamentaux (Bleu)
  - Données & Apprentissage (Vert)
  - Modèles & Paradigmes (Violet)
  - IA Générative (Rose)
  - Applications & Tâches (Jaune)
  - Frameworks & Outils (Indigo)
  - Infrastructure & Compute (Gris)
  - Évaluation & Performance (Cyan)
  - Sécurité & Risques (Rouge)
  - Gouvernance & Éthique (Teal)
- **Disposition type Mendeleïev** avec espaces stratégiques
- **Série Gouvernance séparée** (comme lanthanides/actinides)
- **Modal interactif** pour chaque élément
- **Menu contextuel** au clic droit
- **Définitions détaillées** pour les 107 éléments
- **Design mode sombre** optimisé
- **Responsive design** (desktop, tablette, mobile)
- **Effets hover** avec agrandissement et glow
- **Légende interactive** avec les 10 catégories
- **Section explicative** sur l'interdépendance des éléments IA
- **Fermeture modal multiple** (Escape, clic extérieur, bouton X)
- **Ligne de séparation** visuelle avant la série Gouvernance
- **0 dépendances** - 100% vanilla HTML/CSS/JS

#### Design
- Fond dégradé bleu foncé (#0f0f23 → #1a1a2e)
- Grille CSS 18 colonnes × 9 lignes
- Éléments avec bordures colorées par catégorie
- Backdrop blur pour effet de profondeur
- Animations et transitions fluides
- Typographie optimisée (Segoe UI)

#### Documentation
- README.md complet avec instructions
- LICENSE CC BY-SA 4.0
- CHANGELOG.md pour suivi des versions
- CONTRIBUTING.md guide de contribution
- ELEMENTS.md liste complète
- Attribution des sources et inspirations

#### Crédits
- Inspiré par le "Tableau Périodique de la Crise" (YPSI SAS / Krisium)
- Organisation basée sur le tableau de Mendeleïev
- Conçu par Naully Nicolas

---

## [Non publié] - Roadmap future

### Version 2.1 - Prévue Q2 2026
#### Planifié
- [ ] Barre de recherche d'éléments
- [ ] Filtrage interactif par catégorie
- [ ] Export du tableau en image (PNG/SVG)
- [ ] Export des définitions en PDF
- [ ] Traductions (Anglais, Espagnol, Allemand)
- [ ] Amélioration des performances mobiles
- [ ] Raccourcis clavier (navigation)
- [ ] Accessibilité WCAG 2.1 AA

### Version 2.2 - Prévue Q3 2026
#### Planifié
- [ ] Mode impression optimisé
- [ ] Partage social (Twitter, LinkedIn)
- [ ] Signets/favoris personnels
- [ ] Historique de navigation
- [ ] Mode haut contraste

### Version 3.0 - Prévue Q4 2026
#### Planifié
- [ ] Quiz interactif sur les éléments
- [ ] Système de liens entre éléments liés
- [ ] Timeline historique de l'IA
- [ ] Graphiques de relations entre concepts
- [ ] Mode apprentissage guidé
- [ ] API pour intégrations tierces
- [ ] Version PWA (Progressive Web App)
- [ ] Mode offline complet

---

## Comparaison des versions

| Fonctionnalité | V1.0 | V2.0 |
|----------------|------|------|
| **Nombre d'éléments** | 107 | 114 (+7) |
| **IA Générative** | 12 | 24 (+12) |
| **Mode clair/sombre** | Sombre uniquement | Toggle ✅ |
| **Contact** | Général | Direct ✅ |
| **Responsive** | Oui | Amélioré ✅ |
| **Menu contextuel** | Oui | Oui |
| **Modal** | Oui | Oui |
| **Inspirations** | Krisium | Krisium + IBM ✅ |

---

## Types de modifications

- **Ajouté** : Nouvelles fonctionnalités
- **Modifié** : Changements dans les fonctionnalités existantes
- **Déprécié** : Fonctionnalités qui seront supprimées
- **Supprimé** : Fonctionnalités supprimées
- **Corrigé** : Corrections de bugs
- **Sécurité** : Corrections de vulnérabilités

---

## Conventions de versioning

Ce projet suit le [Semantic Versioning](https://semver.org/lang/fr/) :

- **MAJOR** (X.0.0) : Changements incompatibles avec les versions précédentes
- **MINOR** (2.X.0) : Ajout de fonctionnalités rétrocompatibles
- **PATCH** (2.0.X) : Corrections de bugs rétrocompatibles

---

**Note** : Les dates sont au format ISO 8601 (AAAA-MM-JJ)
