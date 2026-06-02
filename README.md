<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status" />

  <h1>🌐 Projet SAE 1.06 — Site web Atos</h1>
  <p>
    <i>Reproduction d'un site vitrine de l'entreprise Atos réalisée en HTML, CSS et JavaScript dans le cadre de la SAE 1.06.</i>
  </p>
</div>

<br />

## 📖 Table des matières
- [À propos du projet](#-à-propos-du-projet)
- [Fonctionnalités](#-fonctionnalités)
- [Objectifs et Compétences](#-objectifs-et-compétences)
- [Architecture du projet](#-architecture-du-projet)
- [Lancement et Utilisation](#-lancement-et-utilisation)
- [Cadre du Projet (PPP)](#-cadre-du-projet-ppp)

---

## 🚀 À propos du projet

Ce projet consiste en la reproduction d'un site vitrine de l'entreprise **Atos** développé en HTML, CSS et JavaScript. Le site est composé de quatre pages principales : une page d'accueil, une page de présentation des engagements, une page des services et une page de recrutement.

Parmi les fonctionnalités interactives, la page *"Nos Services"* propose des bulles dépliables au clic, et la page *"Rejoignez-nous"* intègre un système dynamique de filtrage des offres par catégorie (stages, alternances, postes).

La navigation est assurée par un header commun à toutes les pages, et se termine par un footer incluant les liens vers les réseaux sociaux (Instagram, LinkedIn, Twitter, YouTube). L'ensemble du style et des interactions repose sur un seul fichier CSS et un seul fichier JavaScript partagés pour des performances et une maintenabilité optimales.

---

## ✨ Fonctionnalités et Pages

| Page | Description |
|------|-------------|
| `Accueil.html` | Page principale avec hero image et présentation des valeurs fondamentales de l'entreprise. |
| `Nos Engagements.html` | Présentation détaillée des engagements sociaux, éthiques et environnementaux d'Atos. |
| `Nos Services.html` | Présentation des services proposés avec un système de **bulles interactives** (dépliables/repliables au clic). |
| `Rejoignez-nous.html` | Espace recrutement avec **filtrage interactif** des offres (onglets Stages / Alternances / Postes à pourvoir). |

---

## 🎯 Objectifs et Compétences

### Objectifs du projet
Le projet visait à concevoir un site web complet en appliquant les bonnes pratiques de développement front-end, avec pour objectif de simuler la réponse au besoin d'un client entreprise (ici, Atos).

### Compétences, Techniques et Savoir-faire Acquis
- **HTML5** : Structuration sémantique des pages web.
- **CSS3** : Maîtrise de la mise en page (Flexbox/Grid) et création d'une charte graphique unifiée (un seul fichier CSS pour tout le site).
- **JavaScript** : Manipulation du DOM pour gérer les interactions utilisateur (filtrage dynamique, éléments dépliables).
- **Relation Client** : Compréhension et retranscription d'un cahier des charges d'entreprise.
- **Formulaire de contact dynamique** : Conception d'interfaces de recueil de données interactives.

---

## 🏗️ Architecture du projet

```text
C2-Atos/
├── Accueil.html
├── Nos Engagements.html
├── Nos Services.html
├── Rejoignez-nous.html
├── Script/
│   └── script.js            # Interactions JavaScript (bulles services + filtres offres)
└── Style/
    ├── style.css            # Feuille de style unique commune à l'ensemble du site
    └── Image/               # Dossier des ressources visuelles classées par page
        ├── Accueil/
        ├── Header/
        ├── Footer/
        ├── Nos Engagements/
        └── Nos Services/
```

---

## 💻 Lancement et Utilisation

Aucune installation complexe ni framework n'est requis.
1. Téléchargez les sources du projet.
2. Ouvrez simplement le fichier `Accueil.html` dans un navigateur web.

> **⚠️ Note importante :** Les liens entre les pages utilisent des chemins absolus (`/Accueil.html` etc.). Pour une navigation parfaitement fonctionnelle, il est **fortement recommandé** d'utiliser un serveur local pour exécuter le site (par exemple l'extension **Live Server** sur Visual Studio Code).

---

## 🎓 Cadre du Projet (PPP)

Ce projet a été réalisé dans le cadre de la **SAE 1.06** de la 1ère année du BUT Informatique.

- **Travail en groupe** : Ce projet a été réalisé en **équipe de 4 personnes**.
- **Travail individuel dans le groupe** : Au sein de cette équipe, j'ai été responsable de la conception et du développement complet (structure et intégration du contenu) de la page **"Nos Engagements"**.
