# Dashboard Admin

Un tableau de bord d'administration moderne et responsive construit avec HTML et CSS Grid.

## 🎯 Aperçu

Ce projet présente un dashboard admin complet avec une mise en page basée sur CSS Grid. Il comprend une barre latérale de navigation, un en-tête avec recherche, une grille de projets et des sections pour les annonces et les tendances.

## ✨ Caractéristiques

- **Layout CSS Grid** : Mise en page moderne avec grilles imbriquées
- **Design Responsive** : La grille des projets s'adapte automatiquement
- **Icônes SVG** : Material Design Icons pour une qualité vectorielle
- **Police Roboto** : Via Google Fonts
- **Effets Interactifs** : Animations hover et transitions fluides
- **Design Moderne** : Couleurs professionnelles et ombres subtiles

## 🛠️ Technologies

- HTML5
- CSS3 (Grid Layout)
- Google Fonts (Roboto)
- Material Design Icons (SVG)

## 📋 Sections

1. **Sidebar** : Navigation principale et secondaire
2. **Header** : 
   - Barre de recherche
   - Notifications
   - Informations utilisateur
   - Boutons d'action
3. **Projects** : Grille de cartes de projets avec actions
4. **Announcements** : Annonces importantes
5. **Trending** : Utilisateurs et projets tendances

## 🎨 Structure CSS Grid

```css
.container {
    display: grid;
    grid-template-columns: 280px 1fr;
    grid-template-rows: auto 1fr;
    grid-template-areas: 
        "sidebar header"
        "sidebar main";
}
```

## 🚀 Installation

1. Clonez le repository
```bash
git clone https://github.com/Bangoura7/admin_dash_bord.git
```

2. Ouvrez `index.html` dans votre navigateur

## 📱 Responsive

Le projet utilise `auto-fit` et `minmax()` pour une grille responsive des projets :

```css
grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
```

## 👤 Auteur

**Abdoul bang's** (@bdasalim)

## 📄 Licence

Ce projet est un projet d'apprentissage créé dans le cadre du curriculum The Odin Project.

## 🙏 Remerciements

- [The Odin Project](https://www.theodinproject.com/) pour le curriculum
- [Material Design Icons](https://materialdesignicons.com/) pour les icônes
- [Google Fonts](https://fonts.google.com/) pour la police Roboto
