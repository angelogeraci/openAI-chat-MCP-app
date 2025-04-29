# openAI-chat-MCP

Interface de chat pour communiquer avec le MCP utilisant OpenAI, inspirée de Claude Desktop.

## Fonctionnalités

- Interface similaire à Claude Desktop
- Communication avec les serveurs MCP
- Sélection parmi des prompts préinstallés
- Possibilité de choisir différents modèles d'OpenAI
- Historique des conversations
- Interface responsive

## Installation

```bash
# Cloner le dépôt
git clone https://github.com/angelogeraci/openAI-chat-MCP-app.git
cd openAI-chat-MCP-app

# Installer les dépendances
npm install

# Configurer les variables d'environnement
cp .env.example .env
# Éditer le fichier .env avec vos clés API

# Lancer l'application en mode développement
npm run dev
```

## Structure du projet

```
/
├── public/           # Fichiers statiques
├── src/              # Code source
│   ├── components/   # Composants React
│   ├── contexts/     # Contextes React
│   ├── hooks/        # Hooks personnalisés
│   ├── lib/          # Fonctions utilitaires
│   ├── pages/        # Pages de l'application
│   ├── prompts/      # Prompts préinstallés
│   └── styles/       # Fichiers de style
├── .env.example      # Exemple de variables d'environnement
└── package.json      # Dépendances et scripts
```

## Technologies utilisées

- Next.js pour le framework frontend/backend
- React pour l'interface utilisateur
- Tailwind CSS pour le styling
- OpenAI API pour la génération de texte
- API MCP pour la communication avec les serveurs
