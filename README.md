# Mini-RPG 3D Multijoueur (LAN)

Ce projet est le prototype d'un mini-jeu de rôle (RPG) 3D multijoueur, jouable en réseau local. Il sert de base à une vision plus large : créer un outil pédagogique permettant de construire des environnements virtuels ludiques et collaboratifs.

## Installation et Lancement

### Prérequis

*   [Node.js](https://nodejs.org/) et npm.

### Étapes

1.  **Installer les dépendances du serveur :**
    ```bash
    cd server
    npm install
    ```

2.  **Démarrer le serveur :**
    *   Pour la production :
        ```bash
        npm start
        ```
    *   Pour le développement (avec redémarrage automatique en cas de modification) :
        ```bash
        npm run dev
        ```
    Le serveur démarrera par défaut sur le port 3000.

3.  **Lancer le jeu :**
    *   Ouvrez simplement le fichier `client/index.html` dans votre navigateur web. Pas besoin de serveur web, tout est géré côté client.
