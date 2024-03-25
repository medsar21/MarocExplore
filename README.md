# MarocExplore

MarocExplore est une plateforme dédiée à la promotion du tourisme au Maroc. Elle permet aux utilisateurs de découvrir et de créer des itinéraires personnalisés mettant en valeur la diversité et la richesse des destinations marocaines.

## Fonctionnalités

- **Authentification des utilisateurs**: Les utilisateurs peuvent créer un compte, se connecter et gérer leur profil.
- **Gestion d'itinéraires**: Les utilisateurs authentifiés peuvent créer des itinéraires personnalisés en ajoutant des destinations et des activités.
- **Recherche d'itinéraires**: Les internautes peuvent visualiser les différents itinéraires sur la plateforme et les filtrer par catégorie ou par durée.
- **Documentation de l'API**: Une documentation détaillée de l'API est fournie pour faciliter son utilisation par d'autres développeurs.

## Technologies Utilisées

- Laravel
- PHP
- MySQL
- HTML
- CSS
- JavaScript

## Installation

1. Cloner le dépôt :

    ```
    git clone https://github.com/votre-utilisateur/maroc-explore.git
    ```

2. Installer les dépendances :

    ```
    composer install
    ```

3. Copier le fichier .env.example et le renommer en .env :

    ```
    cp .env.example .env
    ```

4. Générer une clé d'application :

    ```
    php artisan key:generate
    ```

5. Configurer les informations de la base de données dans le fichier .env.

6. Exécuter les migrations :

    ```
    php artisan migrate
    ```

7. Lancer le serveur :

    ```
    php artisan serve
    ```

