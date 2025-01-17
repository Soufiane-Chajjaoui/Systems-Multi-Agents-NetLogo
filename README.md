# Diffusion d'Information entre Générations avec NetLogo

## 📜 Description du Projet

Ce projet, développé avec **NetLogo**, simule la **diffusion d'information entre générations** dans une population. Il met en évidence la manière dont une information initiale se propage à travers différentes interactions sociales (parents, enfants, pairs). L'objectif est de comprendre comment les caractéristiques des agents influencent cette propagation.

## 🎯 Objectifs

1. **Modéliser les interactions sociales** : Chaque agent représente une personne avec des caractéristiques spécifiques (par exemple, `trusted`, `verified`, `informed`).
2. **Étudier la propagation d'information** : L'information se propage entre les agents via des relations comme parent-enfant, pair-à-pair, ou mentor-apprenti.
3. **Visualiser le processus multi-générationnel** : Observez comment l'information atteint différentes générations avec des dynamiques complexes.

## 🧩 Fonctionnalités Principales

- **Types d'Agents** :
  - `Tortues` : Représentent les individus (personnes).
  - `Patches` : Représentent les zones où vivent ou interagissent les individus.
  - `Liens` : Représentent les relations sociales entre agents (par exemple, parent-enfant).
  
- **Attributs des Agents** :
  - `trusted` : L'agent est digne de confiance.
  - `verified` : L'agent a vérifié l'information.
  - `informed` : L'agent a reçu l'information.
  - `influenced` : L'agent est influencé par d'autres.
  - `transformer` : L'agent modifie et retransmet l'information.

- **Diffusion de l'Information** :
  - Les agents transmettent l'information aux autres selon des règles basées sur leurs attributs et leurs relations.
  - Les générations successives adoptent ou ignorent l'information selon des critères spécifiques.

## 🛠️ Technologies Utilisées

- **NetLogo** : Un environnement puissant pour modéliser et simuler les systèmes multi-agents.
- **Langage de script** : Modélisation des agents et des règles de diffusion.

## 🚀 Instructions d'Utilisation

1. **Installer NetLogo** : Téléchargez et installez [NetLogo](https://ccl.northwestern.edu/netlogo/).
2. **Ouvrir le modèle** :
   - Lancez NetLogo.
   - Chargez le fichier `diffusion-generations.nlogo` dans l'environnement.
3. **Lancer la simulation** :
   - Cliquez sur le bouton `Setup` pour initialiser les agents et l'environnement.
   - Cliquez sur `Go` pour observer la diffusion de l'information.
4. **Paramètres Modifiables** :
   - Ajustez les sliders pour modifier des paramètres tels que la **taille de la population**, le **taux de transmission** et les **caractéristiques des agents**.

## 📊 Résultats Attendues

- **Visualisation graphique** :
  - Observez les agents devenir informés, influencés ou transformés au fil des générations.
  - Analysez les réseaux sociaux et les zones d'interactions via des liens entre tortues.
- **Mesures statistiques** :
  - Taux de diffusion.
  - Nombre d'agents informés par génération.

## 📚 Références

- Documentation officielle de NetLogo : [NetLogo User Manual](https://ccl.northwestern.edu/netlogo/docs/)
- Théories sur la diffusion d'information : [Diffusion Theory Overview](https://en.wikipedia.org/wiki/Diffusion_of_innovations)

## 🖋️ Auteur

Développé par **[Votre Nom]** dans le cadre d'un projet de simulation multi-agents.

## 📂 Structure du Projet

```plaintext
📁 diffusion-generations/
│
├── README.md               # Présentation du projet
├── diffusion-generations.nlogo # Fichier principal NetLogo
└── data/                   # Données supplémentaires (facultatif)
