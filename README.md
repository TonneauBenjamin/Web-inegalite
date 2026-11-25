# 🌍 Web-Inégalité — Plateforme Éducative Interactive

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/fr/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

> Site web interactif de sensibilisation aux inégalités économiques et scolaires dans le monde, intégrant une cartographie visuelle, un classement comparatif et un quiz interactif avec calcul de score en temps réel.

---

## 📌 Présentation du Projet

Ce projet web pédagogique a été conçu pour vulgariser et sensibiliser aux grands enjeux des disparités socio-économiques et éducatives à travers le monde. Il propose une navigation intuitive et interactive pour explorer des indicateurs clés (revenus, scolarisation, indice de Gini).

### Fonctionnalités principales :
- 🏠 **Accueil éditorialisé :** Présentation globale de la problématique et des chiffres marquants.
- 🗺️ **Cartographie interactive (`carte.html`) :** Visualisation spatiale des inégalités de développement par région du monde.
- 📊 **Classement comparatif (`classement.html`) :** Analyse comparative des pays selon les écarts de richesse et d'accès aux services essentiels.
- ❓ **Quiz interactif (`quiz.html`) :** Questionnaire dynamique développé en JavaScript avec calcul automatique du score et feedback utilisateur.
- 📬 **Formulaire de contact (`contact.html`) :** Interface de retour et échanges.

---

## 📁 Architecture des Fichiers

```text
├── HTML/
│   ├── index.html         # Point d'entrée principal
│   ├── accueil.html       # Page d'accueil détaillée
│   ├── carte.html         # Visualisation cartographique
│   ├── classement.html    # Tableaux et classements comparatifs
│   ├── quiz.html          # Quiz interactif
│   └── contact.html       # Page et formulaire de contact
├── CSS/
│   └── style.css          # Feuilles de styles, grille responsive et charte graphique
├── JS/
│   └── script.js          # Logique d'interactivité, validation et moteur du quiz
└── Img/                   # Illustrations, infographies et ressources graphiques
```

---

## 🚀 Lancement en local

Aucune installation complexe ni dépendance externe n'est requise :

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/TonneauBenjamin/Web-inegalite.git
   cd Web-inegalite
   ```
2. Ouvrir le fichier `HTML/index.html` directement dans votre navigateur web, ou lancer un serveur local :
   ```bash
   python3 -m http.server 8080
   ```
3. Accéder à `http://localhost:8080/HTML/index.html`.

---

## 👥 Auteurs

Projet étudiant réalisé par :
- **Benjamin Tonneau**
- Adrien & Arthur
