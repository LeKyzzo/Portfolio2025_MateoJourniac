# Instructions pour Ajouter vos Images

## 📸 Photos à Ajouter

Placez vos images dans ce dossier `assets/images/` avec les noms suivants :

### Photo de Profil
- **Nom** : `profile.jpg` ou `profile.png`
- **Dimensions recommandées** : 500x500px minimum (carré)
- **Format** : JPG ou PNG
- **Utilisé dans** : Section Hero

### Images de Projets
Nommez vos images de projet comme suit :
- `project1.jpg` - E-Commerce Platform
- `project2.jpg` - Task Management App
- `project3.jpg` - Social Media Dashboard
- `project4.jpg` - Mobile Fitness App
- `project5.jpg` - AI Content Generator
- `project6.jpg` - Real Estate Platform

**Dimensions recommandées** : 800x500px (ratio 16:10)
**Format** : JPG ou PNG optimisé

## 🔧 Comment Intégrer les Images

### 1. Photo de Profil
Dans `index.html`, remplacez :
```html
<div class="image-placeholder">
    <i class="fas fa-user-astronaut"></i>
</div>
```

Par :
```html
<div class="image-placeholder">
    <img src="assets/images/profile.jpg" alt="Mateo Journiac" 
         style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

### 2. Images de Projets
Dans `index.html`, pour chaque projet, modifiez :
```html
<div class="project-image">
```

En :
```html
<div class="project-image" style="background: url('assets/images/project1.jpg') center/cover;">
```

## 💡 Conseils

- Optimisez vos images avant de les ajouter (utilisez [TinyPNG](https://tinypng.com))
- Utilisez des images de haute qualité
- Assurez-vous que les images de projets sont représentatives
- Pour la photo de profil, utilisez un fond uni ou flou

## 🎨 Créer un Avatar Temporaire

Si vous n'avez pas encore de photo, vous pouvez :
1. Utiliser [UI Avatars](https://ui-avatars.com/api/?name=Mateo+Journiac&size=500&background=00d4ff&color=fff)
2. Créer un avatar sur [Avatar Maker](https://avatarmaker.com/)
3. Utiliser [Notion Avatar Maker](https://notion-avatar.vercel.app/)

## 📷 Captures d'écran de Projets

Si vous n'avez pas encore d'images de projets, vous pouvez :
1. Faire des captures d'écran de vos projets existants
2. Utiliser des mockups depuis [Mockup World](https://www.mockupworld.co/)
3. Créer des previews avec [Figma](https://www.figma.com/)
4. Utiliser des placeholders temporaires depuis [Unsplash](https://unsplash.com/) en cherchant "web development" ou "dashboard"

## ✅ Checklist

- [ ] Ajouter la photo de profil
- [ ] Ajouter les 6 images de projets
- [ ] Optimiser toutes les images
- [ ] Tester l'affichage sur mobile et desktop
- [ ] Vérifier que les chemins d'accès sont corrects
