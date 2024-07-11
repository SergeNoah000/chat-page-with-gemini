# Chat Page with Gemini

Une interface de chat conviviale et responsive utilisant Google Generative AI (Gemini) pour générer des réponses automatiques. Cette page web utilise HTML, CSS (TailwindCSS), JavaScript, et intègre les bibliothèques marked.js pour le rendu du markdown et highlight.js pour la coloration syntaxique.

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants :

1. Un navigateur web moderne (Google Chrome, Firefox, etc.).
2. Une clé API valide pour utiliser Google Generative AI.

## Fonctionnalités

- Interface de chat responsive.
- Génération de réponses automatiques utilisant Google Generative AI (Gemini).
- Rendu des messages en markdown.
- Coloration syntaxique pour les blocs de code.

## Installation

1. Clonez le dépôt sur votre machine locale.

    ```bash
    git clone https://github.com/SergeNoah000/chat-page-with-gemini.git
    cd chat-page-with-gemini
    ```

2. Ouvrez le fichier `index.html` dans votre éditeur de texte préféré.

3. Remplacez la chaîne `YOUR_API_KEY` par votre clé API valide obtenue à partir de Google Cloud Console.

    ```javascript
    const API_KEY = "YOUR_API_KEY"; // Remplacez par votre clé API valide
    ```

4. Ouvrez le fichier `index.html` dans votre navigateur web.

## Obtenir une clé API

1. Allez sur [Google Cloud Console](https://console.cloud.google.com/).
2. Créez un nouveau projet ou sélectionnez un projet existant.
3. Activez l'API "Generative Language" pour votre projet.
4. Allez dans la section "Identifiants" et créez une clé API.
5. Copiez la clé API et remplacez la chaîne `YOUR_API_KEY` dans le fichier `index.html`.

## Utilisation

1. Tapez votre message dans le champ de saisie en bas de la page.
2. Cliquez sur le bouton d'envoi (icône d'avion en papier) pour envoyer le message.
3. La réponse générée par Google Generative AI s'affichera dans la zone de chat, avec le rendu markdown et la coloration syntaxique pour les blocs de code.

## Structure des fichiers

- `index.html`: La page principale contenant l'interface de chat.
- `README.md`: Ce fichier.

## Contribuer

Les contributions sont les bienvenues ! Si vous avez des suggestions ou des améliorations, veuillez créer une issue ou soumettre une pull request.

## License

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.
