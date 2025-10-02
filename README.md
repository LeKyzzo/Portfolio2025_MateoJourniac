# Portfolio Mateo Journiac 2025

Portfolio professionnel moderne et futuriste présentant mes compétences en développement fullstack et ingénierie logicielle.

## 🚀 Fonctionnalités

- **Design Futuriste** : Interface moderne avec effets glassmorphism, gradients et animations
- **Animations Fluides** : Animations au scroll, effets de particules, typing effect
- **Responsive** : Optimisé pour tous les écrans (mobile, tablette, desktop)
- **Performance** : Code optimisé avec lazy loading et debouncing
- **Interactivité** : Navigation smooth scroll, effets hover 3D sur les projets
- **Sections Complètes** :
  - 🏠 Hero avec typing animation
  - 👤 À propos avec qualités et statistiques animées
  - 💻 Compétences techniques avec barres de progression
  - 🎯 Projets avec hover effects
  - 📋 Expérience professionnelle avec timeline
  - 📧 Formulaire de contact

## 🛠️ Technologies Utilisées

- HTML5
- CSS3 (Animations, Flexbox, Grid)
- JavaScript Vanilla (ES6+)
- Font Awesome (Icônes)

## 📁 Structure du Projet

```
Portfolio2025_MateoJourniac/
├── index.html          # Structure HTML principale
├── styles.css          # Styles CSS avec animations
├── script.js           # Interactions JavaScript
├── assets/             # Dossier pour les ressources
│   └── images/         # Images et photos du portfolio
└── README.md           # Ce fichier
```

## 🎨 Personnalisation

### Couleurs
Les couleurs principales sont définies dans les variables CSS au début de `styles.css` :

```css
:root {
    --primary-color: #00d4ff;      /* Cyan électrique */
    --secondary-color: #7c3aed;    /* Violet */
    --accent-color: #ff006e;       /* Rose */
}
```

### Contenu
1. **Informations personnelles** : Modifier dans `index.html`
   - Nom, titre, description dans la section Hero
   - Email, téléphone, localisation dans la section Contact

2. **Compétences** : Ajuster les pourcentages dans les barres de progression
   - Modifier `data-progress` pour chaque compétence dans `index.html`

3. **Projets** : Ajouter/modifier dans la section Projects
   - Ajouter des images dans `assets/images/`
   - Mettre à jour les liens GitHub et démos

4. **Expérience** : Personnaliser la timeline
   - Dates, titres, entreprises, descriptions

### Ajouter une Photo de Profil
Remplacez le placeholder dans la section Hero de `index.html` :
```html
<div class="image-placeholder">
    <img src="assets/images/profile.jpg" alt="Mateo Journiac" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

### Ajouter des Images de Projets
Ajoutez un style inline dans chaque `project-image` :
```html
<div class="project-image" style="background: url('assets/images/project1.jpg') center/cover;">
```

## 🚀 Lancer le Portfolio

1. **Localement** : Ouvrez simplement `index.html` dans votre navigateur
2. **Serveur local** :
   ```bash
   # Avec Python 3
   python -m http.server 8000
   
   # Avec Node.js
   npx serve
   ```
3. Accédez à `http://localhost:8000`

## 🌐 Déploiement

### GitHub Pages
1. Push le projet sur GitHub
2. Allez dans Settings > Pages
3. Sélectionnez la branche `main` et le dossier `/root`
4. Votre site sera disponible sur `https://lekyzzo.github.io/Portfolio2025_MateoJourniac`

### Netlify / Vercel
1. Créez un compte sur [Netlify](https://netlify.com) ou [Vercel](https://vercel.com)
2. Connectez votre repository GitHub
3. Déployez automatiquement à chaque push

### Hébergement Classique
Uploadez tous les fichiers sur votre serveur web via FTP.

## 📱 Responsive Breakpoints

- **Desktop** : > 1024px
- **Tablette** : 768px - 1024px
- **Mobile** : < 768px
- **Petit Mobile** : < 480px

## ⚡ Performance

- Animations optimisées avec `requestAnimationFrame`
- Lazy loading pour les images
- Debouncing pour les événements scroll
- Transition CSS hardware-accelerated
- Code minifié en production (recommandé)

## 🎯 Fonctionnalités JavaScript

- **Typing Effect** : Animation de texte dynamique dans le Hero
- **Smooth Scroll** : Navigation fluide entre sections
- **Scroll Animations** : Éléments animés à l'apparition avec Intersection Observer
- **Progress Bar** : Barre de progression du scroll en haut de page
- **Particle Effect** : Particules animées en arrière-plan du Hero
- **Counter Animation** : Compteurs animés pour les statistiques
- **3D Hover Effects** : Effets 3D sur les cartes de projets
- **Mobile Menu** : Menu hamburger responsive
- **Form Validation** : Validation du formulaire de contact

## 🔧 Améliorations Futures

- [ ] Ajouter un blog
- [ ] Intégrer un CMS pour gérer le contenu
- [ ] Ajouter un mode clair/sombre toggle
- [ ] Intégrer Google Analytics
- [ ] Ajouter des animations GSAP plus complexes
- [ ] Créer une version multilingue (FR/EN)
- [ ] Ajouter un système de filtrage des projets par technologie
- [ ] Intégrer EmailJS ou FormSpree pour le formulaire de contact
- [ ] Ajouter des témoignages clients
- [ ] Créer une section certifications

## 📄 Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier pour votre propre portfolio.

## 📞 Contact

- **Email** : contact@mateojourniac.com
- **GitHub** : [@LeKyzzo](https://github.com/LeKyzzo)
- **LinkedIn** : [Votre profil LinkedIn]
- **Portfolio** : [URL de votre portfolio]

---

Fait avec ❤️ et beaucoup de ☕ par Mateo Journiac

