# KitchenEdible 🌿🍪

**L'OS Culinaire pour la Cuisine Infusée.**

> *Gérez vos infusions, calculez vos dosages et maîtrisez la décarboxylation avec précision. 100% Privé, 100% Local.*

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Privacy](https://img.shields.io/badge/Privacy-Local_Storage-blue.svg)
![Status](https://img.shields.io/badge/Status-Stable-success.svg)

---

## 📖 À propos

**KitchenEdible** (ou KitchenOS Edible) est une application web progressive (PWA) conçue pour les amateurs de cuisine alternative. Elle résout les problèmes majeurs de la cuisine infusée : le dosage approximatif, la gestion des temps de cuisson et l'organisation des recettes.

L'application est construite pour fonctionner **entièrement dans le navigateur**. Aucune donnée n'est envoyée vers un serveur externe. Vos recettes, votre stock et vos préférences sont sauvegardés localement sur votre appareil.

## ✨ Fonctionnalités

### 🧪 Le Labo (Calculateur de Dosage)
Fini les maths compliquées. Entrez la quantité de fleurs et le taux de THC estimé, l'application calcule :
- Le total de mg de THC dans votre préparation.
- Le dosage précis par portion (par cookie, par part de gâteau).
- Prend en compte la perte naturelle (~12%) due à la décarboxylation.

### ⏱️ Minuteur de Décarboxylation
Un minuteur intelligent avec des préréglages pour activer vos cannabinoïdes sans brûler les terpènes :
- **Four (THC) :** Activation standard.
- **Four (CBD) :** Temps prolongé.
- **Bain-Marie :** Méthode douce.

### 📜 Base de Recettes Intégrée
Plus de **30 recettes** classiques et modernes, inspirées du célèbre *High Times Cannabis Cookbook*, incluant :
- Les bases (Beurre de Marrakech, Huile de Coco, Teintures).
- Plats de résistance (Mac 'n' Cheese, Chili).
- Desserts (Brownies, Caramels).
- Boissons (Bhang, Cocktails).

### 🛒 Gestionnaire de Courses
- Sélectionnez les recettes que vous voulez cuisiner.
- Générez automatiquement un ticket de caisse interactif.
- Ajoutez vos propres articles manuellement.

### 📦 Gestion de Stock (Stash)
Suivez vos différentes variétés (Sativa/Indica/Hybride) et leurs taux de THC pour faciliter vos futurs calculs.

---

## 🚀 Installation & Utilisation

Puisque KitchenEdible est une application statique (HTML/JS/CSS), elle ne nécessite aucune installation complexe (pas de Node.js, pas de base de données).

### Méthode 1 : Utilisation Directe
1. Téléchargez le code source (ZIP) ou clonez ce dépôt.
2. Ouvrez simplement le fichier `index.html` dans votre navigateur (Chrome, Firefox, Safari).
3. Cliquez sur "Lancer l'App".

### Méthode 2 : Serveur Local (Recommandé pour mobile)
Pour une meilleure expérience (et éviter certains blocages CORS stricts des navigateurs), il est conseillé de lancer un petit serveur local.

Si vous avez Python installé :
```bash
# Dans le dossier du projet
python3 -m http.server 8000
# Ouvrez ensuite http://localhost:8000 dans votre navigateur
```

## 🛠️ Technologies

- **HTML5** : Structure sémantique.
- **Tailwind CSS (CDN)** : Design moderne et responsive.
- **React (Standalone/CDN)** : Gestion de l'état et de l'interface sans étape de "build" complexe.
- **Babel (Standalone)** : Compilation JSX à la volée.
- **LocalStorage API** : Persistance des données.

## 🔒 Confidentialité

**KitchenEdible est "Privacy-First".**
- **Zéro Cloud :** Nous n'avons pas de serveurs. Nous ne savons pas qui vous êtes ni ce que vous cuisinez.
- **Zéro Tracking :** Pas de Google Analytics, pas de cookies tiers.
- **Données Locales :** Tout est stocké dans le `localStorage` de votre navigateur. Si vous videz votre cache, vous perdez vos données (pensez à noter vos recettes importantes ailleurs !).

## ⚠️ Avertissement Légal (Disclaimer)

Cette application est fournie à des fins **éducatives et de réduction des risques** uniquement.

- L'auteur ne promeut pas l'usage de substances illégales.
- Les lois concernant le cannabis varient considérablement d'un pays à l'autre. Il est de votre responsabilité de connaître et de respecter les lois en vigueur dans votre juridiction.
- Les calculs de dosage sont des estimations théoriques. La puissance réelle dépend de nombreux facteurs (qualité du produit, précision du four, métabolisme individuel). **Commencez toujours par une petite dose.**

## 📄 Licence

Ce projet est sous licence MIT. Vous êtes libre de le modifier, de le distribuer et de l'utiliser comme bon vous semble.

---
*Développé avec ❤️ et 🌿.*
il y a quelques secondes
