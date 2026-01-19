# Guide de contribution

Merci de votre intérêt pour contribuer au **Tableau Périodique de l'Intelligence Artificielle** ! 🎉

Ce document vous guidera à travers le processus de contribution.

## 📋 Table des matières

- [Code de conduite](#code-de-conduite)
- [Comment puis-je contribuer ?](#comment-puis-je-contribuer)
- [Signaler un bug](#signaler-un-bug)
- [Suggérer une amélioration](#suggérer-une-amélioration)
- [Améliorer les définitions](#améliorer-les-définitions)
- [Processus de Pull Request](#processus-de-pull-request)
- [Conventions de code](#conventions-de-code)
- [Structure des éléments](#structure-des-éléments)

## 📜 Code de conduite

En participant à ce projet, vous acceptez de respecter notre code de conduite :

- 🤝 Respectez tous les contributeurs
- 💬 Soyez ouvert aux retours constructifs
- 🎯 Restez concentré sur l'objectif du projet
- 🌍 Accueillez la diversité des perspectives
- ❤️ Faites preuve d'empathie

## 🤝 Comment puis-je contribuer ?

Il existe plusieurs façons de contribuer à ce projet :

### 1. 🐛 Signaler des bugs
Vous avez trouvé un problème ? Signalez-le !

### 2. 💡 Suggérer des améliorations
Vous avez une idée pour améliorer le projet ? Partagez-la !

### 3. 📝 Améliorer les définitions
Vous trouvez une définition imprécise ? Proposez une correction !

### 4. 🎨 Améliorer le design
Vous avez des compétences en design ? Aidez-nous à améliorer l'interface !

### 5. 🌍 Traduire
Vous parlez plusieurs langues ? Aidez-nous à internationaliser le projet !

### 6. 📚 Améliorer la documentation
La documentation peut toujours être améliorée !

## 🐛 Signaler un bug

Avant de créer un rapport de bug, veuillez :

1. **Vérifier les issues existantes** pour éviter les doublons
2. **Tester avec la dernière version** du projet

### Comment créer un bon rapport de bug

Créez une [issue](https://github.com/votre-username/tableau-periodique-ia/issues/new) en incluant :

- ✅ **Titre clair et descriptif**
- ✅ **Description détaillée** du problème
- ✅ **Étapes pour reproduire** le bug
- ✅ **Comportement attendu** vs comportement observé
- ✅ **Captures d'écran** si pertinent
- ✅ **Environnement** :
  - Navigateur et version
  - Système d'exploitation
  - Taille d'écran (pour problèmes responsive)

**Exemple de titre** :
```
[Bug] Modal ne se ferme pas sur mobile Safari iOS 15
```

## 💡 Suggérer une amélioration

Pour suggérer une amélioration :

1. **Vérifiez la roadmap** dans [CHANGELOG.md](CHANGELOG.md)
2. **Cherchez dans les issues** si l'idée n'existe pas déjà
3. **Créez une issue** avec le label `enhancement`

### Informations à inclure

- 📝 **Description claire** de la fonctionnalité
- 🎯 **Cas d'usage** : Pourquoi c'est utile ?
- 🎨 **Maquettes ou exemples** si possible
- 🔗 **Références** ou projets similaires

**Exemple** :
```markdown
## Fonctionnalité : Recherche d'éléments

### Description
Ajouter une barre de recherche pour filtrer les éléments par nom ou symbole.

### Cas d'usage
L'utilisateur cherche rapidement "transformer" sans parcourir tout le tableau.

### Implémentation suggérée
- Input en haut du tableau
- Filtrage en temps réel
- Surlignage des résultats
```

## 📝 Améliorer les définitions

Les définitions des éléments peuvent toujours être améliorées !

### Critères de qualité

Une bonne définition doit être :
- ✅ **Précise** : Techniquement correcte
- ✅ **Concise** : 2-3 phrases maximum (150-200 caractères)
- ✅ **Accessible** : Compréhensible par un public large
- ✅ **En français** : Langue principale du projet

### Process de modification

1. **Ouvrez une issue** avec le label `définition`
2. Indiquez :
   - Numéro et nom de l'élément
   - Définition actuelle
   - Définition proposée
   - Sources et références
3. Attendez la validation avant de créer une PR

**Exemple** :
```markdown
## Élément #25 - Grand Modèle de Langage (LLM)

### Définition actuelle
"Modèle géant entraîné sur des billions de mots."

### Définition proposée
"Modèle de deep learning entraîné sur des milliards de mots pour comprendre 
et générer du langage naturel avec haute précision."

### Sources
- [Article OpenAI](...)
- [Wikipedia - Large Language Model](...)
```

## 🔄 Processus de Pull Request

### Avant de commencer

1. **Créez une issue** pour discuter des changements importants
2. **Forkez le repository**
3. **Créez une branche** depuis `main`

### Workflow

```bash
# 1. Clonez votre fork
git clone https://github.com/votre-username/tableau-periodique-ia.git
cd tableau-periodique-ia

# 2. Créez une branche
git checkout -b feature/nom-de-votre-feature

# 3. Faites vos modifications

# 4. Testez localement
# Ouvrez index.html dans plusieurs navigateurs

# 5. Commitez
git add .
git commit -m "Add: description de vos changements"

# 6. Pushez vers votre fork
git push origin feature/nom-de-votre-feature

# 7. Créez une Pull Request sur GitHub
```

### Checklist PR

Avant de soumettre votre PR, vérifiez :

- [ ] Le code fonctionne sur Chrome, Firefox, Safari
- [ ] Le design est responsive (mobile, tablette, desktop)
- [ ] Pas de console errors
- [ ] Les nouvelles définitions ont des sources
- [ ] Le code suit les conventions du projet
- [ ] La documentation est mise à jour si nécessaire
- [ ] Les commits ont des messages clairs

### Template de Pull Request

```markdown
## Description
Décrivez vos changements en quelques phrases.

## Type de changement
- [ ] Bug fix
- [ ] Nouvelle fonctionnalité
- [ ] Amélioration de définition
- [ ] Amélioration du design
- [ ] Documentation

## Tests effectués
- [ ] Chrome (version X)
- [ ] Firefox (version X)
- [ ] Safari (version X)
- [ ] Mobile (iOS/Android)

## Captures d'écran
Si pertinent, ajoutez des captures d'écran.

## Issues liées
Closes #123
```

## 💻 Conventions de code

### HTML

```html
<!-- Utilisez l'indentation à 4 espaces -->
<div class="element architecture">
    <div class="element-number">1</div>
    <div class="element-symbol">Tr</div>
    <div class="element-name">Transformeur</div>
</div>
```

### CSS

```css
/* Utilisez des commentaires clairs */
/* Regroupez les propriétés par catégorie */
.element {
    /* Positionnement */
    display: flex;
    position: relative;
    
    /* Dimensions */
    width: 70px;
    height: 70px;
    
    /* Apparence */
    background: rgba(30, 30, 50, 0.6);
    border: 2px solid;
    border-radius: 6px;
    
    /* Transition */
    transition: all 0.3s ease;
}
```

### JavaScript

```javascript
// Utilisez des noms de variables descriptifs
// Commentez les fonctions complexes
// Préférez const et let à var

/**
 * Affiche le modal avec les informations de l'élément
 * @param {Object} element - L'élément à afficher
 */
function showModal(element) {
    const modal = document.getElementById('modal');
    // ...
}
```

## 🧩 Structure des éléments

Chaque élément dans le tableau suit cette structure :

```javascript
{
    number: 1,                    // Numéro unique (1-107)
    symbol: "Tr",                 // Symbole (2-4 lettres, capitalize)
    name: "Transformeur",         // Nom complet en français
    category: "architecture",     // Catégorie (lowercase)
    description: "Description"    // 150-200 caractères max
}
```

### Catégories disponibles

```javascript
const categories = {
    architecture: "Architecture & Fondamentaux",
    donnees: "Données & Apprentissage",
    modeles: "Modèles & Paradigmes",
    generative: "IA Générative",
    applications: "Applications & Tâches",
    frameworks: "Frameworks & Outils",
    infrastructure: "Infrastructure & Compute",
    evaluation: "Évaluation & Performance",
    securite: "Sécurité & Risques",
    gouvernance: "Gouvernance & Éthique"
};
```

## 📚 Ressources

### Documentation technique
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [JavaScript ES6+](https://es6-features.org/)

### Design
- [Dribbble - Periodic Table](https://dribbble.com/search/periodic-table)
- [Color Hunt](https://colorhunt.co/) - Palettes de couleurs

### IA et ML
- [Papers With Code](https://paperswithcode.com/)
- [Hugging Face](https://huggingface.co/)
- [ArXiv](https://arxiv.org/)

## ❓ Questions ?

- 📧 **Email** : naully@example.com
- 💬 **Discussions** : Utilisez les [GitHub Discussions](https://github.com/votre-username/tableau-periodique-ia/discussions)
- 🐛 **Issues** : Pour les bugs et suggestions

## 🙏 Remerciements

Merci de prendre le temps de contribuer ! Chaque contribution, petite ou grande, aide à améliorer ce projet. 

---

**Happy Contributing! 🚀**
