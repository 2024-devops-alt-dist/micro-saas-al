# 🌿 MycoNote

> Le carnet de terrain numérique pour explorateurs mycologiques

![Bolet](img/bolet.webp)

---

## 🧭 Présentation

**MycoNote** est une application mobile pensée pour les passionnés de champignons. Elle permet de documenter les découvertes mycologiques sur le terrain, même hors ligne, grâce à une interface fluide et adaptée aux conditions de terrain.

---

## 🎯 Objectifs

- Centraliser les **photos**, **notes**, **localisations** et **conditions météo** d'une observation.
- Faciliter l’**identification**, la **consultation** et le **partage** d'espèces observées.
- Offrir une **expérience utilisateur fluide** même sans connexion Internet.

---

## 💡 Objectifs UX

- **Simplicité d’utilisation** en pleine nature : interface épurée, accessible à une main.
- **Rapidité d’accès** aux fonctionnalités clés : création de fiche, recherche, observation.
- **Lisibilité** dans des conditions extérieures (contraste fort, typographie claire).
- **Valorisation du contenu utilisateur** : mise en avant visuelle des observations partagées.

---

## 👣 Parcours utilisateur prototypé

<img src="img/Accueil_2.png" alt="Maquette Accueil" width="300">

### Page d’accueil : 
- Accès direct aux dernières **observations partagées**
- **Barre de recherche** + **filtrage** pour naviguer rapidement
- Navigation par **onglets fixes** en bas :
  - Accueil
  - Recherche
  - Nouvelle observation
  - Mon carnet

### Observation :
- Accès à une fiche : titre, image, date, auteur
- Clic sur une carte → détail complet
- Bouton pour **ajouter** sa propre observation en un clic

---

## 🖌️ Choix UI (Interface utilisateur)

- **Mode sombre** par défaut pour un confort visuel en extérieur
- **Accent vert naturel** `#009951` pour les éléments interactifs
- **Typographie claire et lisible** (ex. : sans-serif, poids bold pour les titres)
- **Cartes visuelles** avec photos en plein écran pour valoriser le contenu communautaire
- **Icônes épurées** pour navigation simple et intuitive

---

## 🧑‍🤝‍🧑 Public cible

- Mycologues (pro/amateurs)
- Randonneurs
- Étudiants en biologie, écologie
- Guides nature
- Associations naturalistes

---

## ⚙️ Fonctionnalités

### Fonctionnalité principale : Carnet d'observation
- Fiches complètes : photo, notes, date, lieu, météo, espèce
- Recherche et tri par filtre
- Mode hors-ligne (PWA)
- Possibilité de rendre une fiche publique

### Fonctionnalités secondaires
- Fiches descriptives d’espèces
- Suggestions d’identification
- Export PDF
- Alertes saisonnières
- Partage entre utilisateurs
- Enregistreur audio

---

## 🧱 Zoning

![Zoning](img/zoning.png)

---

## 🆚 Concurrence

- **iNaturalist** : généraliste, peu ciblé champignons
- **Champignouf** : fort sur l'identification, faible sur l'organisation

---

## 🧪 Stack technique

| Composant     | Technologie             |
|---------------|--------------------------|
| Frontend      | React + TypeScript       |
| Backend       | Node.js + Express (TS)   |
| Base de données | PostgreSQL             |

## Maqette

Lien vers la maquette du proget sur [Figma](https://www.figma.com/design/Gsyj6WjLJOUFlxgHjpBtKG/micro-saas?node-id=0-1&t=CT8iHCkJoz7bWyrF-1)