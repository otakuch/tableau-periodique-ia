# Liste complète des 114 éléments

Ce document liste tous les éléments du Tableau Périodique de l'IA avec leurs définitions complètes.

**Version 2.0** - 114 éléments (+7 depuis V1.0)

## Table des matières

- [Architecture & Fondamentaux (1-12)](#architecture--fondamentaux-1-12)
- [Données & Apprentissage (13-24)](#données--apprentissage-13-24)
- [Modèles & Paradigmes (25-38)](#modèles--paradigmes-25-38)
- [IA Générative (39-62)](#ia-générative-39-62) ⭐ **24 éléments**
- [Applications & Tâches (63-74)](#applications--tâches-63-74)
- [Frameworks & Outils (75-86)](#frameworks--outils-75-86)
- [Infrastructure & Compute (87-94)](#infrastructure--compute-87-94)
- [Évaluation & Performance (95-102)](#évaluation--performance-95-102)
- [Gouvernance & Éthique (103-114)](#gouvernance--éthique-103-114)

---

## Architecture & Fondamentaux (1-12)

Les briques de base des réseaux de neurones et architectures modernes.

### 1. Tr - Transformeur
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Architecture révolutionnaire basée sur l'attention, fondement des LLM modernes. Permet le traitement parallèle et la compréhension contextuelle profonde.

### 2. At - Attention
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Mécanisme qui permet au modèle de se concentrer sur les parties pertinentes de l'entrée. Le cœur du transformeur.

### 3. Cn - Convolution
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Opération mathématique essentielle pour l'analyse d'images. Détecte les motifs locaux en balayant l'image avec des filtres.

### 4. Rn - Récurrent
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Architecture traitant les séquences pas à pas avec mémoire. Prédécesseur des transformeurs pour le langage.

### 5. Ga - GAN
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Deux réseaux qui s'affrontent : un générateur crée, un discriminateur juge. Révolution pour la génération d'images réalistes.

### 6. Ae - Autoencodeur
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Compresse puis reconstruit les données. Apprend les représentations essentielles en éliminant le superflu.

### 7. Em - Embedding
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Représentation vectorielle dense des mots ou concepts. Capture le sens dans un espace mathématique.

### 8. Tk - Tokenisation
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Découpage du texte en unités traitables. Première étape cruciale avant tout traitement linguistique.

### 9. Ly - Couche
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Unité de traitement empilable dans un réseau. Chaque couche extrait des features de plus en plus abstraites.

### 10. Ac - Activation
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Fonction non-linéaire qui permet au réseau d'apprendre des patterns complexes. Sans elle, tout serait linéaire.

### 11. Dp - Dropout
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Technique de régularisation : désactive aléatoirement des neurones pendant l'entraînement. Évite le surapprentissage.

### 12. Bn - Normalisation
**Catégorie** : Architecture & Fondamentaux  
**Définition** : Stabilise l'apprentissage en normalisant les activations. Accélère la convergence et améliore la performance.

---

## IA Générative (39-62) ⭐ ENRICHIE V2.0

La famille la plus importante avec 24 éléments couvrant toutes les modalités de génération.

### Techniques de base (39-50)

### 39. Pm - Prompt
**Catégorie** : IA Générative  
**Définition** : Instruction donnée au modèle. L'art du prompting détermine la qualité de la réponse générée.

### 40. Cot - Chain-of-Thought
**Catégorie** : IA Générative  
**Définition** : Technique qui encourage le modèle à raisonner étape par étape. Améliore drastiquement les capacités de résolution de problèmes.

### 41. Tem - Température
**Catégorie** : IA Générative  
**Définition** : Contrôle la créativité du modèle. Basse = prévisible, haute = créatif mais risqué.

### 42. Top - Top-p/Top-k
**Catégorie** : IA Générative  
**Définition** : Méthodes de sampling qui limitent les choix de tokens. Équilibre entre diversité et cohérence.

### 43. Sam - Sampling
**Catégorie** : IA Générative  
**Définition** : Stratégie de sélection du prochain token. Détermine le caractère déterministe ou aléatoire de la génération.

### 44. Gen - Génération
**Catégorie** : IA Générative  
**Définition** : Production de nouveau contenu par le modèle. Cœur de l'IA générative : texte, image, code, audio.

### 45. Cre - Créativité
**Catégorie** : IA Générative  
**Définition** : Capacité à produire du contenu original et pertinent. Balance entre respect des contraintes et innovation.

### 46. Stl - Style
**Catégorie** : IA Générative  
**Définition** : Adaptation du ton, format et personnalité. Permet au modèle de mimer différents styles d'écriture ou artistiques.

### 47. Ctx - Contexte
**Catégorie** : IA Générative  
**Définition** : Fenêtre d'information accessible au modèle. Plus elle est grande, meilleure est la compréhension globale.

### 48. Mem - Mémoire
**Catégorie** : IA Générative  
**Définition** : Capacité à retenir les informations des échanges précédents. Essentielle pour des conversations cohérentes.

### 49. Per - Persona
**Catégorie** : IA Générative  
**Définition** : Personnalité et rôle assignés au modèle. Définit comment il se comporte et répond.

### 50. Sys - System Prompt
**Catégorie** : IA Générative  
**Définition** : Instructions permanentes qui définissent le comportement du modèle. Le fondement de sa personnalité et de ses règles.

### 🆕 Modalités Text-to-X (51-54)

### 51. T2i - Text-to-Image ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Génération d'images à partir de descriptions textuelles. Midjourney, DALL-E, Stable Diffusion transforment les mots en visuels.  
**Exemples** : DALL-E 3, Midjourney, Stable Diffusion XL, Firefly

### 52. T2v - Text-to-Video ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Création de vidéos à partir de prompts textuels. Sora, Runway Gen-2 révolutionnent la production vidéo.  
**Exemples** : Sora, Runway Gen-2, Pika 1.0

### 53. T2a - Text-to-Audio ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Synthèse de musique et sons à partir de descriptions. AudioCraft, MusicGen créent des compositions originales.  
**Exemples** : AudioCraft, MusicGen, AudioLDM

### 54. T23 - Text-to-3D ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Génération de modèles 3D à partir de texte. DreamFusion, Point-E transforment les descriptions en objets 3D.  
**Exemples** : DreamFusion, Point-E, Shap-E

### 🆕 Transformations Image/Video/Audio (55-58)

### 55. I2i - Image-to-Image ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Transformation d'images selon des instructions. Style transfer, super-résolution, colorisation automatique.  
**Exemples** : ControlNet, InstantID, Pix2Pix

### 56. I2v - Image-to-Video ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Animation d'images statiques en vidéos. Pika, Genmo transforment les photos en séquences animées.  
**Exemples** : Pika, Genmo, Stable Video Diffusion

### 57. V2v - Video-to-Video ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Transformation de vidéos avec conservation de structure. Deepfake, changement de style, restauration vidéo.  
**Exemples** : Runway Gen-1, CoDeF, Video-P2P

### 58. A2a - Audio-to-Audio ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Transformation audio : voix, musique, effets sonores. Conversion de style musical, voice cloning.  
**Exemples** : ElevenLabs, Resemble AI, Descript

### 🆕 Applications spécialisées (59-62)

### 59. T2c - Text-to-Code ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Génération de code à partir de descriptions naturelles. GitHub Copilot, Claude Code, GPT-4 écrivent des programmes.  
**Exemples** : GitHub Copilot, Claude Code, Cursor

### 60. Inp - Inpainting ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Remplissage intelligent de zones manquantes. Photoshop Generative Fill, reconstruction d'images partielles.  
**Exemples** : Photoshop Generative Fill, DALL-E Inpainting

### 61. Out - Outpainting ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Extension d'images au-delà des bordures. DALL-E Outpainting, création de contexte autour d'une image.  
**Exemples** : DALL-E Outpainting, Stable Diffusion Outpainting

### 62. Upc - Upscaling ⭐ NOUVEAU
**Catégorie** : IA Générative  
**Définition** : Amélioration de résolution avec IA. Topaz Gigapixel, Real-ESRGAN augmentent la qualité d'image.  
**Exemples** : Topaz Gigapixel AI, Real-ESRGAN, Magnific AI

---

## Gouvernance & Éthique (103-114)

Les principes et réglementations encadrant le développement responsable de l'IA.

### 103. Biais - Biais
**Catégorie** : Gouvernance & Éthique  
**Définition** : Discrimination systématique dans les prédictions. Reflète et amplifie les préjugés présents dans les données.

### 104. Eq - Équité
**Catégorie** : Gouvernance & Éthique  
**Définition** : Traitement juste de tous les groupes. Objectif difficile : équité statistique vs équité individuelle.

### 105. Xpl - Explicabilité
**Catégorie** : Gouvernance & Éthique  
**Définition** : Capacité à expliquer les décisions du modèle. Essentielle pour la confiance, la réglementation et le debugging.

### 106. Trp - Transparence
**Catégorie** : Gouvernance & Éthique  
**Définition** : Ouverture sur le fonctionnement, les données, les limitations. Documenter honnêtement les capacités et risques.

### 107. Alg - Alignement
**Catégorie** : Gouvernance & Éthique  
**Définition** : Conformité du comportement aux valeurs humaines. Défi majeur : faire en sorte que l'IA fasse ce qu'on veut vraiment.

### 108. Rgpd - RGPD
**Catégorie** : Gouvernance & Éthique  
**Définition** : Règlement européen sur la protection des données. Impacte fortement le développement et l'utilisation de l'IA.

### 109. Aud - Audit
**Catégorie** : Gouvernance & Éthique  
**Définition** : Évaluation indépendante du système d'IA. Vérification de la conformité, performance, sécurité, éthique.

### 110. Imp - Analyse d'Impact
**Catégorie** : Gouvernance & Éthique  
**Définition** : Évaluation des conséquences sociales et éthiques. Obligatoire pour les systèmes à haut risque.

### 111. Iso - ISO 42001
**Catégorie** : Gouvernance & Éthique  
**Définition** : Première norme internationale pour les systèmes de management de l'IA. Cadre de gouvernance et de gestion des risques.

### 112. Hal - Hallucination
**Catégorie** : Sécurité & Risques  
**Définition** : Génération confiante d'informations fausses. Problème majeur des LLM : invente des faits de manière crédible.

### 113. Jlb - Jailbreak
**Catégorie** : Sécurité & Risques  
**Définition** : Contournement des garde-fous de sécurité. Techniques pour faire dire au modèle ce qu'il ne devrait pas.

### 114. Pvt - Confidentialité
**Catégorie** : Sécurité & Risques  
**Définition** : Protection des données sensibles dans l'entraînement et l'utilisation. Risque de mémorisation et de fuite.

---

## Statistiques V2.0

- **Total des éléments** : 114 (+7 vs V1.0)
- **Nombre de familles** : 10
- **Famille la plus grande** : IA Générative (24 éléments, +12)
- **Famille la plus petite** : Sécurité & Risques (3 éléments)
- **Nouveaux éléments** : 12 en IA Générative

### Répartition par famille

| Famille | V1.0 | V2.0 | Évolution |
|---------|------|------|-----------|
| Architecture & Fondamentaux | 12 | 12 | - |
| Données & Apprentissage | 12 | 12 | - |
| Modèles & Paradigmes | 14 | 14 | - |
| **IA Générative** | **12** | **24** | **+12** 🆕 |
| Applications & Tâches | 12 | 12 | - |
| Frameworks & Outils | 12 | 12 | - |
| Infrastructure & Compute | 8 | 8 | - |
| Évaluation & Performance | 8 | 8 | - |
| Sécurité & Risques | 8 | 3 | Réorganisé |
| Gouvernance & Éthique | 9 | 9 | - |

---

**Document généré automatiquement**  
Version 2.0 - 2026  
Tableau Périodique de l'IA par Naully Nicolas
