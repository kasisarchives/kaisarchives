<div align="center">

# Kaïs.R — Portfolio Digital

**Le code au service de l'essentiel.** <br>
*Un espace pensé pour la lisibilité, la fluidité et les détails qui comptent.*

[![Voir le site](https://img.shields.io/badge/Voir_le_site_Live-111111?style=for-the-badge&logo=vercel&logoColor=white)](https://kasisarchives.github.io/portfolio/)

</div>

<br>

Salut ! 👋 Moi c'est **Kaïs**, étudiant en MIAGE et intégrateur web junior. 

Bienvenue dans le code source de mon portfolio. Pour ce projet personnel, j'aurais pu utiliser un framework JavaScript complexe ou un template tout fait, mais j'ai préféré faire l'inverse : revenir aux bases. 

L'idée était simple : voir jusqu'où on pouvait pousser l'expérience utilisateur (UX) avec du HTML, du CSS et du JS, en soignant vraiment chaque partie.

---

### ✦ L'obsession du détail

Je suis convaincu que le minimalisme n'est pas juste "faire vide", mais enlever tout ce qui empêche de comprendre le message. Pour ce site, je me suis imposé quelques règles de design :

- 📐 **L'espace a un sens :** J'ai utilisé un système d'espacements stricts (basé sur 8px) pour que l'œil sache naturellement comment grouper les informations (loi de proximité).
- 👁️ **Zéro friction cognitive :** Seulement deux typographies (`Syne` pour les titres, `Inter` pour le texte), des contrastes étudiés et un Dark Mode natif qui ne pique pas les yeux.
- 👆 **Pensé pour les pouces :** Sur mobile, toutes les zones cliquables font au moins 44x44px. C'est la loi de Fitts, et c'est beaucoup plus agréable à utiliser au quotidien.

<br>

### 🛠️ Sous le capot

Ici, juste ce qu'il faut pour que l'interface soit vivante et rapide.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)

- **Scroll & Fluidité :** J'utilise `Lenis` pour un smooth scroll qui respecte le navigateur, couplé à `GSAP` pour des micro-interactions douces.
- **Performance avant tout :** Les animations se limitent aux propriétés `transform` et `opacity`. Résultat : un rendu à 60fps géré par la carte graphique, sans faire chauffer les téléphones.

<br>

### 📂 Structure des fichiers

Une arborescence plate et lisible, pour s'y retrouver tout de suite :

```text
📁 kaisarchives/
├── 📄 index.html           # Point d'entrée & Hero
├── 📄 projects.html        # Portfolio & Réalisations
├── 📄 about.html           # Parcours & Stack technique
├── 📄 contact.html         # Formulaire de contact sécurisé
├── 📄 article-*.html       # Pages dédiées aux notes éditoriales
├── 🎨 style.css            # Grilles, variables CSS & Responsive
└── ⚡ script.js            # Logique de l'interface & Scroll reveal
