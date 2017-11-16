# Cahier des charges du blog

> Interprétation possible de la demande client.

## Contexte

### Présentation
Un responsable de formation d'une école de développement web souhaite mettre un blog à disposition de ses élèves.


### Objectif
... en réalité il s'agit d'un projet de blog standard à but pédagogique :nerd_face: (blog de développeurs souhaitant partager leur parcours lors de la formation O'clock) ...

### Budget
A partir de 2000€ HT (soit 5 jours).

### Délai
Deux semaines à compter de la validation du devis (et réception de l'acompte de 30%).

## Specs fonctionnelles

### Apparence
Ambiance "espace" (cosmos). Site responsive.
### Contenus
- articles,
- des auteurs,
- des catégories (front, back, collaboration, vie du développeur).

Les contenus seraient créés à terme via une interface d'administration (à mettre en option, dans un premier temps nous vous fournirons des contenus).

### Interactions services
- Liens et/ou partages vers les réseaux sociaux.

### Langue
En français.

### Arborescence

- Accueil
- Page catégorie (articles filtrés par catégorie) :
    - Teamback
    - Teamfront
    - Collaboration
    - MaVieDeDev
- Page article (détail)
- (Contact)
- (Mentions légales)
- (Admin)

### Navigation

- Un menu principal vers les catégories et l'accueil
- En responsive, un menu burger apparait dans lequel se trouvent les liens
- On clique sur le titre ou le texte de l'article pour afficher le détail
- Un menu secondaire (dans le footer ou ailleurs) pour lier vers admin, contact, mentions légales.

### Templates

#### Layout global

- Un menu avec
    - titre/logo.
    - liens vers les catégories.
- Une image d'en-tête avec titre + slogan (baseline).
- "Sidebar" à droite qui regroupe
    - Champ de recherche
    - Liste des catégories
    - Liste des auteurs
- Pied de page
    - Liens vers les réseaux sociaux.
    - Liens vers admin, contact, mentions légales.

#### Liste des articles

- Un article
    - Un titre (cliquable)
    - Un résumé (cliquable)
    - Date
    - Auteur
    - Catégorie
- Pagination "Précedente" et "Suivante"

### Contraintes techniques

- Site responsive.
- Compatibilité dernières versions des navigateurs.

## Specs techniques

### Description précises des données manipulées.

- articles
    - titre
    - date du publication
    - auteur
- auteurs
- catégories

> A compléter

### Architecture logicielle choisie.

- blog en HTML/CSS/PHP/MySQL.

> A compléter
