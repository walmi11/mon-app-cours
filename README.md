# Quartz

**Quartz** est une application locale de prise de notes et de gestion de cours sur ordinateur (via Electron et Next.js). Avec son interface moderne *glassmorphism* aux teintes violettes, Quartz permet d'organiser facilement vos matières, de modifier vos cours avec un éditeur enrichi, et de suivre vos tâches.

## Fonctionnalités

- **Tableau de bord dynamique** : Suivi du nombre de cours, de matières et de tâches restantes.
- **Gestion des Matières** : Création de matières personnalisées avec des icônes uniques.
- **Éditeur de Cours** : Rédigez vos notes de cours avec un éditeur intuitif et une sauvegarde automatique locale.
- **Thème Visuel Quartz** : Design contemporain *glassmorphism*, animations fluides et tons violets élégants.
- **100% Local (Privacy First)** : Toutes vos données sont stockées de façon sécurisée directement sur votre ordinateur (data/db.json).

## Technologies

- **Next.js 15+** (App Router)
- **Tailwind CSS** (Styles complexes et gradients)
- **Lucide React** (Icônes)
- **Electron** (Conversion en application de bureau native)

## Installation & Utilisation

`ash
# Installer les dépendances
npm install

# Lancer en mode développement (Web)
npm run dev

# Construire l'application
npm run build

# Lancer la version Bureau (Electron)
npm run electron
`

> Note : Les données sont persistées dans le dossier data de votre installation locale.
