# Plateforme de Devis Rénovation

Une plateforme moderne pour la gestion des devis de rénovation, intégrant Tally, Strapi et Next.js.

## Structure du Projet

```
renovation-quotes/
├── frontend/          # Application Next.js
│   ├── src/          # Code source
│   └── public/       # Assets statiques
└── backend/          # API Strapi
    ├── src/          # Code source
    └── config/       # Configuration
```

## Technologies Utilisées

- **Frontend**: Next.js 14 avec TypeScript et Tailwind CSS
- **Backend**: Strapi CMS
- **Formulaire**: Tally.so
- **Base de données**: PostgreSQL

## Installation

### Frontend

```bash
cd frontend
npm install
npm run dev
```

### Backend

```bash
cd backend
npm install
npm run develop
```

## Configuration

1. Créez un compte Tally.so et configurez votre formulaire
2. Configurez les variables d'environnement dans `.env.local`
3. Démarrez le serveur de développement

## Licence

MIT 