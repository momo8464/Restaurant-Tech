# 🍽️ Restaurant Tech

Bienvenue sur le projet **Restaurant Tech**, un site web vitrine pour un restaurant spécialisé dans une cuisine africaine moderne, authentique et savoureuse.

Le site permet aux visiteurs de découvrir le restaurant, consulter les différents plats proposés et contacter l'établissement pour obtenir des informations ou effectuer une commande.

---

## 📌 Présentation du projet

**Restaurant Tech** est un projet de développement web réalisé avec **HTML5 et CSS3**.

L'objectif du projet est de concevoir un site web moderne, simple, responsive et facile à utiliser, tout en mettant en valeur la richesse de la cuisine africaine.

Le site est composé de trois pages principales :

* 🏠 **Accueil** : présentation du restaurant et de son histoire.
* 🍛 **Menu** : présentation des plats et de leurs prix.
* 📞 **Contact** : formulaire permettant aux visiteurs de contacter le restaurant.

---

## 🌐 Aperçu du site

Le site propose une interface adaptée aux ordinateurs, tablettes et smartphones.

Les visiteurs peuvent :

* Découvrir le restaurant.
* Consulter les spécialités proposées.
* Voir les prix des plats.
* Accéder à la localisation du restaurant.
* Envoyer un message via le formulaire de contact.
* Contacter directement le restaurant par e-mail.
* Appeler directement le restaurant depuis un téléphone.

---

## 🗂️ Structure du projet

```text
Restaurant-Tech/
│
├── README.md
│
├── index.html
├── menu.html
├── contact.html
│
├── css/
│   ├── principal.css
│   ├── menu.css
│   └── contact.css
│
└── img/
    ├── logo.png
    ├── image principale.jpg
    ├── riz accompagné de poulet africain.jpeg
    ├── riz gras au poulet.png
    ├── tchêpe.jpg
    └── telephone_logo.png
```

---

## 🏠 Page d'accueil

La page `index.html` constitue la page principale du site.

Elle contient :

* Le logo du Restaurant Tech.
* Une barre de navigation.
* Une image principale du restaurant.
* Une présentation du restaurant.
* Une section consacrée à l'histoire du restaurant.
* Un bouton permettant d'accéder au menu.
* Une carte Google Maps pour localiser le restaurant.
* Un footer contenant les informations de contact.

### Navigation

La navigation permet d'accéder facilement aux différentes pages :

```text
Accueil
À propos
Menu
Contact
```

---

## 🍛 Page Menu

La page `menu.html` présente les différents plats proposés par le restaurant.

### Plats disponibles

| Plat                              |       Prix |
| --------------------------------- | ---------: |
| Riz accompagné de poulet africain | 3 500 FCFA |
| Riz gras au poulet                | 3 000 FCFA |
| Tchêpe                            | 2 500 FCFA |

Chaque plat possède :

* Une image.
* Un nom.
* Une description.
* Un prix.
* Un bouton **Commander**.

Le bouton **Commander** redirige le visiteur vers la page Contact.

---

## 📞 Page Contact

La page `contact.html` permet aux visiteurs de contacter le restaurant.

Le formulaire contient les champs suivants :

* Nom.
* Prénom.
* Adresse e-mail.
* Numéro de téléphone.
* Message.

Deux boutons sont disponibles :

* **Envoyer** : permet de soumettre le formulaire.
* **Effacer** : permet de réinitialiser les champs du formulaire.

La page contient également les informations permettant de contacter directement le restaurant par e-mail ou par téléphone.

---

## 🎨 Design

Le design du site repose principalement sur une identité visuelle inspirée de la cuisine africaine.

### Couleurs principales

| Couleur           | Code      |
| ----------------- | --------- |
| 🟢 Vert principal | `#0f6b4b` |
| 🟢 Vert foncé     | `#094832` |
| 🟡 Jaune          | `#f4b942` |
| ⚪ Blanc           | `#ffffff` |
| ⚫ Noir            | `#1f1f1f` |
| 🌫️ Gris          | `#666666` |
| 🌫️ Fond          | `#f7f7f7` |

Le vert représente la couleur principale de l'identité visuelle du restaurant, tandis que le jaune est utilisé comme couleur d'accent.

---

## 🛠️ Technologies utilisées

### HTML5

HTML5 est utilisé pour créer la structure des pages du site.

Les éléments sémantiques utilisés comprennent notamment :

* `header`
* `nav`
* `main`
* `section`
* `article`
* `footer`
* `form`
* `fieldset`

### CSS3

CSS3 est utilisé pour la mise en forme du site :

* Mise en page.
* Couleurs.
* Typographie.
* Espacements.
* Boutons.
* Formulaires.
* Cartes de plats.
* Animations au survol.
* Responsive design.

---

## 📱 Responsive Design

Le site est conçu pour s'adapter aux différentes tailles d'écran.

Il fonctionne notamment sur :

* 💻 Ordinateurs de bureau.
* 💻 Ordinateurs portables.
* 📱 Smartphones.
* 📱 Petits écrans.
* 📟 Tablettes.

Des **Media Queries CSS** sont utilisées afin d'adapter automatiquement la mise en page.

---

## ✨ Fonctionnalités actuelles

* [x] Page d'accueil.
* [x] Présentation du restaurant.
* [x] Section « À propos ».
* [x] Page Menu.
* [x] Présentation des plats.
* [x] Affichage des prix en FCFA.
* [x] Boutons de commande.
* [x] Page Contact.
* [x] Formulaire de contact.
* [x] Lien e-mail.
* [x] Lien téléphone.
* [x] Localisation Google Maps.
* [x] Navigation entre les pages.
* [x] Design responsive.
* [x] Effets au survol.
* [x] Footer sur les différentes pages.

---

## 📂 Organisation des fichiers CSS

Chaque page possède son propre fichier CSS.

### Page d'accueil

```text
index.html
    ↓
css/principal.css
```

### Page Menu

```text
menu.html
    ↓
css/menu.css
```

### Page Contact

```text
contact.html
    ↓
css/contact.css
```

Cette organisation permet de conserver un projet clair, organisé et facile à maintenir.

---

## 🚀 Installation et utilisation

Aucune installation particulière n'est nécessaire pour utiliser le site.

### 1. Télécharger le projet

Téléchargez ou clonez le dépôt GitHub.

### 2. Ouvrir le dossier

Ouvrez le dossier :

```text
Restaurant-Tech/
```

### 3. Lancer le site

Ouvrez le fichier :

```text
index.html
```

avec un navigateur web.

Le site peut être consulté avec :

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Opera
* Safari

---

## 🔮 Améliorations futures

Le projet pourra évoluer avec l'ajout de nouvelles fonctionnalités.

### Fonctionnalités prévues

* [ ] Ajouter JavaScript.
* [ ] Ajouter un menu mobile avec bouton hamburger.
* [ ] Ajouter davantage de plats.
* [ ] Ajouter une galerie photos.
* [ ] Ajouter une section témoignages clients.
* [ ] Ajouter les réseaux sociaux du restaurant.
* [ ] Ajouter un bouton WhatsApp.
* [ ] Ajouter un véritable système de commande.
* [ ] Ajouter un panier.
* [ ] Ajouter un système de paiement en ligne.
* [ ] Connecter le formulaire de contact à un serveur.
* [ ] Ajouter une base de données.
* [ ] Ajouter un espace administrateur.
* [ ] Ajouter des animations plus avancées.
* [ ] Améliorer l'accessibilité.
* [ ] Optimiser davantage les performances du site.

---

## 🎯 Objectifs du projet

Ce projet a notamment pour objectifs de :

* Mettre en pratique les connaissances en HTML et CSS.
* Apprendre à organiser un projet web.
* Créer une interface responsive.
* Améliorer la structure et la qualité du code.
* Comprendre l'utilisation de GitHub.
* Construire progressivement un projet pouvant être présenté dans un portfolio.

---

## 👨‍💻 Auteur

**M. KONE Mohamed**

Projet de développement web réalisé dans un cadre personnel et éducatif.

---

## 📄 Licence

Ce projet est un projet personnel/éducatif.

Le contenu, le design et les éléments originaux du projet sont réservés à leur auteur.

---

## ❤️ Restaurant Tech

> **Restaurant Tech — La tradition africaine rencontre la modernité.**
