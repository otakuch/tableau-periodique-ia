# Liste complète des 107 éléments

Ce document liste tous les éléments du Tableau Périodique de l'IA avec leurs définitions complètes.

## Table des matières

- [Architecture & Fondamentaux (1-12)](#architecture--fondamentaux-1-12)
- [Données & Apprentissage (13-24)](#données--apprentissage-13-24)
- [Modèles & Paradigmes (25-38)](#modèles--paradigmes-25-38)
- [IA Générative (39-50)](#ia-générative-39-50)
- [Applications & Tâches (51-62)](#applications--tâches-51-62)
- [Frameworks & Outils (63-74)](#frameworks--outils-63-74)
- [Infrastructure & Compute (75-82)](#infrastructure--compute-75-82)
- [Évaluation & Performance (83-90)](#évaluation--performance-83-90)
- [Sécurité & Risques (91-98)](#sécurité--risques-91-98)
- [Gouvernance & Éthique (99-107)](#gouvernance--éthique-99-107)

---

## Architecture & Fondamentaux (1-12)

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

## Données & Apprentissage (13-24)

### 13. Dt - Dataset
**Catégorie** : Données & Apprentissage  
**Définition** : Ensemble de données d'entraînement. La qualité des données détermine la qualité du modèle final.

### 14. Et - Étiquetage
**Catégorie** : Données & Apprentissage  
**Définition** : Annotation manuelle des données pour l'apprentissage supervisé. Processus coûteux mais indispensable.

### 15. Ag - Augmentation
**Catégorie** : Données & Apprentissage  
**Définition** : Création de variations artificielles des données. Multiplie le dataset sans collecter de nouvelles données.

### 16. Sp - Supervisé
**Catégorie** : Données & Apprentissage  
**Définition** : Apprentissage avec des exemples étiquetés. Le modèle apprend à partir de paires question-réponse.

### 17. Ns - Non-Supervisé
**Catégorie** : Données & Apprentissage  
**Définition** : Apprentissage sans étiquettes : le modèle découvre les structures cachées dans les données par lui-même.

### 18. Rf - Renforcement
**Catégorie** : Données & Apprentissage  
**Définition** : Apprentissage par essai-erreur avec récompenses. L'agent apprend la stratégie optimale pour maximiser le score.

### 19. Tf - Transfer Learning
**Catégorie** : Données & Apprentissage  
**Définition** : Réutilisation d'un modèle pré-entraîné. Économise temps et ressources en capitalisant sur l'apprentissage existant.

### 20. Fa - Fine-tuning
**Catégorie** : Données & Apprentissage  
**Définition** : Ajustement d'un modèle pré-entraîné sur des données spécifiques. Spécialise le modèle pour votre tâche.

### 21. Pr - Pré-entraînement
**Catégorie** : Données & Apprentissage  
**Définition** : Apprentissage initial sur d'énormes volumes de données. Créé la base de connaissances du modèle.

### 22. Bs - Batch
**Catégorie** : Données & Apprentissage  
**Définition** : Nombre d'exemples traités simultanément. Compromis entre vitesse d'entraînement et qualité de convergence.

### 23. Ep - Époque
**Catégorie** : Données & Apprentissage  
**Définition** : Un passage complet sur tout le dataset. Plus d'époques = plus d'apprentissage, mais risque de surapprentissage.

### 24. Lr - Taux d'Apprentissage
**Catégorie** : Données & Apprentissage  
**Définition** : Vitesse à laquelle le modèle ajuste ses poids. Trop rapide = instabilité, trop lent = convergence interminable.

---

## Modèles & Paradigmes (25-38)

### 25. Llm - Grand Modèle de Langage
**Catégorie** : Modèles & Paradigmes  
**Définition** : Modèle géant entraîné sur des billions de mots. Capable de comprendre et générer du texte avec une précision impressionnante.

### 26. Vm - Modèle de Vision
**Catégorie** : Modèles & Paradigmes  
**Définition** : Réseau spécialisé dans l'analyse d'images. Détecte, classifie, segmente les éléments visuels.

### 27. Mm - Multimodal
**Catégorie** : Modèles & Paradigmes  
**Définition** : Combine plusieurs types de données : texte, image, audio. Comprend les relations entre différentes modalités.

### 28. Df - Diffusion
**Catégorie** : Modèles & Paradigmes  
**Définition** : Génère des images en partant du bruit. Processus itératif de débruitage qui crée des visuels époustouflants.

### 29. Rag - RAG
**Catégorie** : Modèles & Paradigmes  
**Définition** : Récupère des documents pertinents puis génère une réponse. Combine recherche et génération pour des réponses factuelles.

### 30. Ag - Agent
**Catégorie** : Modèles & Paradigmes  
**Définition** : IA autonome qui perçoit, décide et agit. Peut utiliser des outils et mener des tâches complexes de bout en bout.

### 31. Moe - Mixture of Experts
**Catégorie** : Modèles & Paradigmes  
**Définition** : Architecture avec plusieurs sous-modèles spécialisés. Un routeur dirige chaque requête vers l'expert approprié.

### 32. Ds - Distillation
**Catégorie** : Modèles & Paradigmes  
**Définition** : Compression d'un grand modèle vers un petit. Transfert de connaissances du professeur vers l'élève.

### 33. Qt - Quantification
**Catégorie** : Modèles & Paradigmes  
**Définition** : Réduction de la précision numérique des poids. Diminue drastiquement la taille et accélère l'inférence.

### 34. Pr - Élagage
**Catégorie** : Modèles & Paradigmes  
**Définition** : Suppression des connexions peu importantes. Allège le modèle sans sacrifier la performance.

### 35. Lo - LoRA
**Catégorie** : Modèles & Paradigmes  
**Définition** : Adaptation efficace en entraînant seulement des matrices de faible rang. Fine-tuning rapide avec peu de mémoire.

### 36. Fs - Few-Shot
**Catégorie** : Modèles & Paradigmes  
**Définition** : Apprentissage à partir de quelques exemples seulement. Capacité d'adaptation rapide à de nouvelles tâches.

### 37. Zs - Zero-Shot
**Catégorie** : Modèles & Paradigmes  
**Définition** : Performance sur des tâches jamais vues. Le modèle généralise uniquement grâce à ses connaissances générales.

### 38. Ic - In-Context Learning
**Catégorie** : Modèles & Paradigmes  
**Définition** : Apprentissage par simple présentation d'exemples dans le prompt. Pas de mise à jour des poids nécessaire.

---

## IA Générative (39-50)

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

---

## Applications & Tâches (51-62)

### 51. Cb - Chatbot
**Catégorie** : Applications & Tâches  
**Définition** : Assistant conversationnel intelligent. Répond aux questions, aide les utilisateurs, automatise le support.

### 52. Cv - Vision par Ordinateur
**Catégorie** : Applications & Tâches  
**Définition** : IA qui 'voit' et analyse les images. Détection d'objets, reconnaissance faciale, analyse médicale.

### 53. Nl - Traitement du Langage
**Catégorie** : Applications & Tâches  
**Définition** : Compréhension et manipulation du texte. Analyse de sentiment, extraction d'informations, compréhension sémantique.

### 54. Ts - Synthèse Vocale
**Catégorie** : Applications & Tâches  
**Définition** : Conversion du texte en parole naturelle. Voix réalistes pour assistants vocaux et accessibilité.

### 55. St - Transcription
**Catégorie** : Applications & Tâches  
**Définition** : Transformation de l'audio en texte écrit. Sous-titrage automatique, prise de notes, analyse de conversations.

### 56. Ig - Génération d'Images
**Catégorie** : Applications & Tâches  
**Définition** : Création d'images à partir de descriptions textuelles. Révolutionne le design, l'art et la création de contenu.

### 57. Cd - Génération de Code
**Catégorie** : Applications & Tâches  
**Définition** : Écriture automatique de programmes informatiques. Copilote du développeur, génération de tests, debugging.

### 58. Rs - Résumé
**Catégorie** : Applications & Tâches  
**Définition** : Condensation automatique de textes longs. Extraction de l'essentiel, gain de temps considérable.

### 59. Td - Traduction
**Catégorie** : Applications & Tâches  
**Définition** : Conversion entre langues avec compréhension contextuelle. Bien au-delà de la traduction mot à mot.

### 60. Cl - Classification
**Catégorie** : Applications & Tâches  
**Définition** : Attribution de catégories à des données. Tri automatique, détection de spam, diagnostic médical.

### 61. Sg - Segmentation
**Catégorie** : Applications & Tâches  
**Définition** : Découpage précis des éléments dans une image. Identification pixel par pixel de chaque objet.

### 62. Dt - Détection
**Catégorie** : Applications & Tâches  
**Définition** : Localisation d'objets dans les images ou vidéos. Surveillance, véhicules autonomes, analyse de scènes.

---

## Frameworks & Outils (63-74)

### 63. Pt - PyTorch
**Catégorie** : Frameworks & Outils  
**Définition** : Framework de deep learning le plus populaire en recherche. Flexible, pythonique, écosystème riche.

### 64. Tf - TensorFlow
**Catégorie** : Frameworks & Outils  
**Définition** : Plateforme ML de Google, solide pour la production. Déploiement facile, optimisation matérielle excellente.

### 65. Hf - Hugging Face
**Catégorie** : Frameworks & Outils  
**Définition** : Hub central des modèles pré-entraînés. Bibliothèques puissantes pour NLP et vision, communauté active.

### 66. Sk - Scikit-learn
**Catégorie** : Frameworks & Outils  
**Définition** : Bibliothèque Python pour ML classique. Simple, efficace, parfaite pour débuter et pour les modèles traditionnels.

### 67. Ke - Keras
**Catégorie** : Frameworks & Outils  
**Définition** : API haut niveau pour construire des réseaux neuronaux rapidement. Interface intuitive, excellent pour prototyper.

### 68. Jx - JAX
**Catégorie** : Frameworks & Outils  
**Définition** : Framework de Google pour calcul numérique haute performance. Transformations automatiques de code, idéal pour la recherche.

### 69. Lc - LangChain
**Catégorie** : Frameworks & Outils  
**Définition** : Framework pour construire des applications LLM. Orchestration d'agents, chaînage de prompts, intégrations multiples.

### 70. Ll - LlamaIndex
**Catégorie** : Frameworks & Outils  
**Définition** : Outil pour connecter des LLM à vos données. Construction d'index intelligents, RAG optimisé.

### 71. Ol - Ollama
**Catégorie** : Frameworks & Outils  
**Définition** : Exécution locale de LLM sur votre machine. Confidentialité totale, pas de dépendance cloud.

### 72. Wd - Weights & Biases
**Catégorie** : Frameworks & Outils  
**Définition** : Plateforme de tracking d'expériences ML. Visualisation, comparaison, collaboration sur les entraînements.

### 73. Ml - MLflow
**Catégorie** : Frameworks & Outils  
**Définition** : Gestion du cycle de vie ML : tracking, packaging, déploiement. Open source, agnostique des frameworks.

### 74. Gr - Gradio
**Catégorie** : Frameworks & Outils  
**Définition** : Création rapide d'interfaces web pour modèles ML. Démo et partage en quelques lignes de code.

---

## Infrastructure & Compute (75-82)

### 75. Gpu - GPU
**Catégorie** : Infrastructure & Compute  
**Définition** : Processeur graphique devenu indispensable pour l'IA. Parallélisation massive pour entraînement et inférence rapides.

### 76. Tpu - TPU
**Catégorie** : Infrastructure & Compute  
**Définition** : Puce spécialisée de Google pour le deep learning. Optimisée spécifiquement pour les opérations matricielles.

### 77. Cld - Cloud
**Catégorie** : Infrastructure & Compute  
**Définition** : Infrastructure à la demande pour l'IA. Scalabilité illimitée, paiement à l'usage, GPU puissants disponibles.

### 78. Dis - Distribué
**Catégorie** : Infrastructure & Compute  
**Définition** : Entraînement réparti sur plusieurs machines. Seule solution pour les modèles géants et les datasets massifs.

### 79. Mlo - MLOps
**Catégorie** : Infrastructure & Compute  
**Définition** : DevOps appliqué au machine learning. Automatisation, monitoring, versioning des modèles en production.

### 80. Pip - Pipeline
**Catégorie** : Infrastructure & Compute  
**Définition** : Chaîne automatisée de traitement des données et modèles. De l'ingestion à la production sans intervention manuelle.

### 81. Cnt - Conteneur
**Catégorie** : Infrastructure & Compute  
**Définition** : Encapsulation de l'environnement d'exécution. Reproductibilité parfaite, déploiement simplifié.

### 82. Scl - Scalabilité
**Catégorie** : Infrastructure & Compute  
**Définition** : Capacité à gérer une charge croissante. Horizontale (plus de machines) ou verticale (machines plus puissantes).

---

## Évaluation & Performance (83-90)

### 83. Acc - Précision
**Catégorie** : Évaluation & Performance  
**Définition** : Proportion de prédictions correctes. Métrique de base mais insuffisante pour les datasets déséquilibrés.

### 84. F1 - Score F1
**Catégorie** : Évaluation & Performance  
**Définition** : Équilibre entre précision et rappel. Métrique plus robuste que l'accuracy seule.

### 85. Ppx - Perplexité
**Catégorie** : Évaluation & Performance  
**Définition** : Mesure de la qualité d'un modèle de langage. Plus elle est basse, mieux le modèle prédit le texte.

### 86. Ble - Score BLEU
**Catégorie** : Évaluation & Performance  
**Définition** : Évaluation de la qualité de traduction. Compare la sortie du modèle aux traductions humaines de référence.

### 87. Lat - Latence
**Catégorie** : Évaluation & Performance  
**Définition** : Temps de réponse du modèle. Crucial pour les applications temps réel et l'expérience utilisateur.

### 88. Thr - Débit
**Catégorie** : Évaluation & Performance  
**Définition** : Nombre de requêtes traitées par seconde. Mesure de la capacité de production du système.

### 89. Ram - Mémoire
**Catégorie** : Évaluation & Performance  
**Définition** : Consommation de RAM/VRAM du modèle. Détermine la taille maximale déployable et le coût d'infrastructure.

### 90. Flp - FLOPS
**Catégorie** : Évaluation & Performance  
**Définition** : Opérations en virgule flottante par seconde. Mesure de la puissance de calcul brute nécessaire.

---

## Sécurité & Risques (91-98)

### 91. Hal - Hallucination
**Catégorie** : Sécurité & Risques  
**Définition** : Génération confiante d'informations fausses. Problème majeur des LLM : invente des faits de manière crédible.

### 92. Jlb - Jailbreak
**Catégorie** : Sécurité & Risques  
**Définition** : Contournement des garde-fous de sécurité. Techniques pour faire dire au modèle ce qu'il ne devrait pas.

### 93. Adv - Adversarial
**Catégorie** : Sécurité & Risques  
**Définition** : Exemples malicieusement modifiés pour tromper le modèle. Perturbations invisibles qui causent des erreurs grossières.

### 94. Rob - Robustesse
**Catégorie** : Sécurité & Risques  
**Définition** : Résistance aux perturbations et cas limites. Capacité à maintenir la performance en conditions réelles.

### 95. Pvt - Confidentialité
**Catégorie** : Sécurité & Risques  
**Définition** : Protection des données sensibles dans l'entraînement et l'utilisation. Risque de mémorisation et de fuite.

### 96. Psn - Empoisonnement
**Catégorie** : Sécurité & Risques  
**Définition** : Injection de données malveillantes dans le dataset. Corruption délibérée du comportement du modèle.

### 97. Vol - Vol de Modèle
**Catégorie** : Sécurité & Risques  
**Définition** : Extraction non autorisée des poids ou du comportement. Risque de propriété intellectuelle et de sécurité.

### 98. Fui - Fuite de Données
**Catégorie** : Sécurité & Risques  
**Définition** : Révélation involontaire d'informations d'entraînement. Le modèle peut répéter des données confidentielles.

---

## Gouvernance & Éthique (99-107)

### 99. Biais - Biais
**Catégorie** : Gouvernance & Éthique  
**Définition** : Discrimination systématique dans les prédictions. Reflète et amplifie les préjugés présents dans les données.

### 100. Eq - Équité
**Catégorie** : Gouvernance & Éthique  
**Définition** : Traitement juste de tous les groupes. Objectif difficile : équité statistique vs équité individuelle.

### 101. Xpl - Explicabilité
**Catégorie** : Gouvernance & Éthique  
**Définition** : Capacité à expliquer les décisions du modèle. Essentielle pour la confiance, la réglementation et le debugging.

### 102. Trp - Transparence
**Catégorie** : Gouvernance & Éthique  
**Définition** : Ouverture sur le fonctionnement, les données, les limitations. Documenter honnêtement les capacités et risques.

### 103. Alg - Alignement
**Catégorie** : Gouvernance & Éthique  
**Définition** : Conformité du comportement aux valeurs humaines. Défi majeur : faire en sorte que l'IA fasse ce qu'on veut vraiment.

### 104. Rgpd - RGPD
**Catégorie** : Gouvernance & Éthique  
**Définition** : Règlement européen sur la protection des données. Impacte fortement le développement et l'utilisation de l'IA.

### 105. Aud - Audit
**Catégorie** : Gouvernance & Éthique  
**Définition** : Évaluation indépendante du système d'IA. Vérification de la conformité, performance, sécurité, éthique.

### 106. Imp - Analyse d'Impact
**Catégorie** : Gouvernance & Éthique  
**Définition** : Évaluation des conséquences sociales et éthiques. Obligatoire pour les systèmes à haut risque.

### 107. Iso - ISO 42001
**Catégorie** : Gouvernance & Éthique  
**Définition** : Première norme internationale pour les systèmes de management de l'IA. Cadre de gouvernance et de gestion des risques pour un développement responsable de l'intelligence artificielle.

---

## Statistiques

- **Total des éléments** : 107
- **Nombre de familles** : 10
- **Famille la plus grande** : Modèles & Paradigmes (14 éléments)
- **Famille la plus petite** : Infrastructure & Compute (8 éléments)

---

**Document généré automatiquement**  
Version 1.0 - 2026  
Tableau Périodique de l'IA par Naully Nicolas
