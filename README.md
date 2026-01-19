# 🧠 Tableau Périodique de l'Intelligence Artificielle

![Version](https://img.shields.io/badge/version-1.0-blue)
![License](https://img.shields.io/badge/license-CC%20BY--SA%204.0-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

Une représentation interactive et éducative des 107 concepts essentiels de l'Intelligence Artificielle, organisés selon une structure inspirée du tableau périodique des éléments de Mendeleïev.

![Aperçu du Tableau Périodique de l'IA](preview.png)

## 📋 Table des matières

- [À propos](#à-propos)
- [Démo en ligne](#démo-en-ligne)
- [Fonctionnalités](#fonctionnalités)
- [Structure](#structure)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Les 10 familles](#les-10-familles)
- [Technologies](#technologies)
- [Sources et inspirations](#sources-et-inspirations)
- [Contribuer](#contribuer)
- [Licence](#licence)
- [Auteur](#auteur)

## 🎯 À propos

Ce projet présente **107 éléments essentiels de l'IA** organisés en **10 familles thématiques**, dans une interface interactive inspirée du tableau périodique des éléments chimiques. Chaque élément représente un concept, une technologie, un framework ou une pratique fondamentale dans le domaine de l'intelligence artificielle.

### Objectifs du projet

- 📚 **Éducatif** : Fournir une vue d'ensemble structurée des concepts d'IA
- 🎨 **Visuel** : Utiliser une représentation familière et intuitive
- 🔍 **Interactif** : Permettre l'exploration détaillée de chaque élément
- 🌍 **Accessible** : Interface en français, responsive et moderne

## 🌐 Démo en ligne

[Voir la démo en ligne](https://votre-username.github.io/tableau-periodique-ia/)

## ✨ Fonctionnalités

### Interface interactive
- ✅ **Disposition type Mendeleïev** avec espaces stratégiques
- ✅ **107 éléments cliquables** avec définitions détaillées
- ✅ **10 catégories colorées** pour une identification rapide
- ✅ **Modal d'information** au clic sur chaque élément
- ✅ **Effets hover** avec agrandissement et glow
- ✅ **Design mode sombre** optimisé pour la lecture
- ✅ **Responsive design** (desktop, tablette, mobile)
- ✅ **Légende interactive** en bas du tableau
- ✅ **Fermeture modal** (Escape, clic extérieur, bouton X)

### Organisation visuelle
- 🔵 **Architecture & Fondamentaux** (Bleu) : Transformeur, Attention, CNN, etc.
- 🟢 **Données & Apprentissage** (Vert) : Dataset, Étiquetage, Fine-tuning, etc.
- 🟣 **Modèles & Paradigmes** (Violet) : LLM, RAG, Agents, etc.
- 🌸 **IA Générative** (Rose) : Prompt, Chain-of-Thought, Température, etc.
- 🟡 **Applications & Tâches** (Jaune) : Chatbot, Vision, Traduction, etc.
- 🔷 **Frameworks & Outils** (Indigo) : PyTorch, TensorFlow, Hugging Face, etc.
- ⚪ **Infrastructure & Compute** (Gris) : GPU, Cloud, MLOps, etc.
- 🔷 **Évaluation & Performance** (Cyan) : Précision, F1, Latence, etc.
- 🔴 **Sécurité & Risques** (Rouge) : Hallucination, Jailbreak, etc.
- 🟦 **Gouvernance & Éthique** (Teal) : Biais, RGPD, ISO 42001, etc.

## 📁 Structure

```
tableau-periodique-ia/
├── index.html                 # Fichier HTML principal
├── README.md                  # Ce fichier
├── LICENSE                    # Licence CC BY-SA 4.0
├── CHANGELOG.md              # Historique des versions
├── preview.png               # Capture d'écran du projet
└── docs/
    ├── ELEMENTS.md           # Liste détaillée des 107 éléments
    └── CONTRIBUTING.md       # Guide de contribution
```

## 🚀 Installation

### Option 1 : Téléchargement direct

1. Téléchargez le fichier `index.html`
2. Ouvrez-le dans votre navigateur web préféré
3. Aucune installation supplémentaire nécessaire !

### Option 2 : Clone du repository

```bash
git clone https://github.com/votre-username/tableau-periodique-ia.git
cd tableau-periodique-ia
```

Ensuite, ouvrez `index.html` dans votre navigateur.

### Option 3 : Hébergement local

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (npx)
npx http-server

# Accédez ensuite à http://localhost:8000
```

## 💻 Utilisation

### Navigation de base
1. **Survolez** un élément pour voir l'effet d'agrandissement
2. **Cliquez** sur un élément pour afficher sa définition détaillée
3. **Fermez** le modal avec :
   - La touche `Escape`
   - Le bouton `×` en haut à droite
   - Un clic en dehors du modal

### Exploration par catégorie
- Consultez la **légende** en bas du tableau
- Chaque **couleur** représente une famille thématique
- Les éléments sont **organisés par période** comme dans le tableau de Mendeleïev

### Responsive
- **Desktop** : Grille 18 colonnes, éléments 70×70px
- **Tablette** : Grille adaptative, éléments 60×50px
- **Mobile** : Grille compacte, éléments 40px (noms masqués)

## 🎓 Les 10 familles

| Famille | Éléments | Couleur | Description |
|---------|----------|---------|-------------|
| **Architecture & Fondamentaux** | 1-12 | 🔵 Bleu | Structures de base des réseaux de neurones |
| **Données & Apprentissage** | 13-24 | 🟢 Vert | Méthodes d'entraînement et gestion des données |
| **Modèles & Paradigmes** | 25-38 | 🟣 Violet | Types de modèles et approches d'apprentissage |
| **IA Générative** | 39-50 | 🌸 Rose | Techniques de génération de contenu |
| **Applications & Tâches** | 51-62 | 🟡 Jaune | Domaines d'application de l'IA |
| **Frameworks & Outils** | 63-74 | 🔷 Indigo | Outils de développement et plateformes |
| **Infrastructure & Compute** | 75-82 | ⚪ Gris | Matériel et infrastructure |
| **Évaluation & Performance** | 83-90 | 🔷 Cyan | Métriques et mesures de performance |
| **Sécurité & Risques** | 91-98 | 🔴 Rouge | Menaces et vulnérabilités |
| **Gouvernance & Éthique** | 99-107 | 🟦 Teal | Réglementation et considérations éthiques |

## 🛠️ Technologies

- **HTML5** : Structure sémantique
- **CSS3** : 
  - CSS Grid pour la disposition type Mendeleïev
  - Flexbox pour les composants
  - Variables CSS pour la gestion des couleurs
  - Animations et transitions fluides
  - Media queries pour le responsive
- **JavaScript Vanilla** : 
  - Génération dynamique des éléments
  - Gestion des interactions utilisateur
  - Modal et événements clavier

**Aucune dépendance externe** - Le projet fonctionne entièrement en standalone !

## 📚 Sources et inspirations

### Inspiration principale
- **Tableau Périodique de la Crise** par [YPSI SAS / Krisium](https://krisium.fr/tableau)
  - Inspiration pour le concept de tableau périodique thématique
  - Design et disposition en mode sombre
  - Structure des modals informatifs

### Ressources techniques
- **Tableau périodique des éléments chimiques** (Mendeleïev)
  - Structure en périodes et groupes
  - Organisation logique par familles
  
### Sources de contenu
- Documentation officielle des frameworks et outils mentionnés
- Littérature académique en IA et Machine Learning
- Standards et normes (ISO 42001, RGPD)
- Glossaires techniques de référence

### Outils et méthodologies
- Conception collaborative avec Claude (Anthropic)
- Design itératif et tests utilisateurs
- Validation des définitions techniques

## 🤝 Contribuer

Les contributions sont les bienvenues ! Voici comment participer :

### Signaler un bug
Ouvrez une [issue](https://github.com/votre-username/tableau-periodique-ia/issues) en décrivant :
- Le problème rencontré
- Les étapes pour le reproduire
- Votre navigateur et système d'exploitation

### Proposer une amélioration
1. **Fork** le projet
2. Créez une **branche** pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. **Commit** vos changements (`git commit -m 'Add some AmazingFeature'`)
4. **Push** vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une **Pull Request**

### Améliorer les définitions
Si vous trouvez une définition imprécise ou incomplète :
- Ouvrez une issue avec la correction proposée
- Incluez vos sources et références

Consultez [CONTRIBUTING.md](docs/CONTRIBUTING.md) pour plus de détails.

## 📄 Licence

Ce projet est sous licence **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**.

Vous êtes libre de :
- ✅ **Partager** : copier et redistribuer le matériel
- ✅ **Adapter** : remixer, transformer et créer à partir du matériel

Sous les conditions suivantes :
- 📝 **Attribution** : Vous devez créditer l'œuvre
- 🔄 **ShareAlike** : Vous devez distribuer vos contributions sous la même licence

Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 👤 Auteur

**Naully Nicolas**

- 🌐 Portfolio : [naully.com](https://naully.com) *(à adapter)*
- 💼 LinkedIn : [linkedin.com/in/naully-nicolas](https://linkedin.com/in/naully-nicolas) *(à adapter)*
- 📧 Email : naully@example.com *(à adapter)*

## 🙏 Remerciements

- **YPSI SAS / Krisium** pour l'inspiration du concept de tableau périodique thématique
- **Dmitri Mendeleïev** pour l'organisation originale du tableau périodique
- La **communauté IA** pour les retours et suggestions
- **Anthropic** pour les outils de conception

## 📊 Statistiques du projet

- **107 éléments** couvrant tout l'écosystème IA
- **10 familles thématiques** pour une classification logique
- **0 dépendances** externes
- **100% vanilla** HTML/CSS/JS
- **Responsive** sur tous les appareils

## 🗺️ Roadmap

### Version 1.0 ✅
- [x] 107 éléments avec définitions
- [x] Disposition type Mendeleïev
- [x] Design mode sombre
- [x] Modal interactif
- [x] Responsive design

### Version 1.1 (À venir)
- [ ] Mode clair/sombre toggle
- [ ] Recherche d'éléments
- [ ] Filtrage par catégorie
- [ ] Export en image/PDF
- [ ] Traductions (EN, ES, DE)

### Version 2.0 (Futur)
- [ ] Quiz interactif
- [ ] Liens entre éléments
- [ ] Timeline historique
- [ ] Graphiques de relations

---

<div align="center">

**⭐ Si ce projet vous plaît, n'hésitez pas à lui donner une étoile !**

Fait avec ❤️ et ☕ par Naully Nicolas | Version 1.0 - 2026

[⬆ Retour en haut](#-tableau-périodique-de-lintelligence-artificielle)

</div>
