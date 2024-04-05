# projet-6

just stream it

Récupération d'une copie du "dépôt"

    git clone https://github.com/mohammediabdelkarim/projet-6

Récupération de l'API

    https://github.com/OpenClassrooms-Student-Center/OCMovies-API-EN-FR

Installation / Création du serveur local

Les instructions figurent dans le README de l'API (s'y référer pour plus d'informations) :

    Installation et exécution de l'application avec pipenv

    Cloner ce dépôt de code à l'aide de la commande $ git clone clone https://github.com/OpenClassrooms-Student-Center/OCMovies-API-EN-FR.git (vous pouvez également télécharger le code en temps qu'archive zip)
    Rendez-vous depuis un terminal à la racine du répertoire ocmovies-api-fr avec la commande $ cd ocmovies-api-fr
    Installez les dépendances du projet à l'aide de la commande pipenv install
    Créer et alimenter la base de données à l'aide de la commande pipenv run python manage.py create_db
    Démarrer le serveur avec pipenv run python manage.py runserver

Lorsque le serveur fonctionne, après l'étape 5 de la procédure, l'API OCMovies peut être interrogée à partir des points d'entrée commençant par l'url de base http://localhost:8000/api/v1/. Le point d'entrée principal permettant de consulter les films est http://localhost:8000/api/v1/titles.

Les étapes 1 à 4 ne sont requises que pout l'installation initiale. Pour les lancements ultérieurs du serveur de l'API, il suffit d'exécuter l'étape 5 à partir du répertoire racine du projet.

    Installation et exécution de l'application sans pipenv (avec venv et pip)

    Cloner ce dépôt de code à l'aide de la commande $ git clone clone https://github.com/OpenClassrooms-Student-Center/OCMovies-API-EN-FR.git (vous pouvez également télécharger le code en temps qu'archive zip)
    Rendez-vous depuis un terminal à la racine du répertoire ocmovies-api-fr avec la commande $ cd ocmovies-api-fr
    Créer un environnement virtuel pour le projet avec $ python -m venv env sous windows ou $ python3 -m venv env sous macos ou linux.
    Activez l'environnement virtuel avec $ env\Scripts\activate sous windows ou $ source env/bin/activate sous macos ou linux.
    Installez les dépendances du projet avec la commande $ pip install -r requirements.txt
    Créer et alimenter la base de données avec la commande $ python manage.py create_db
    Démarrer le serveur avec $ python manage.py runserver

Lorsque le serveur fonctionne, après l'étape 7 de la procédure, l'API OCMovies peut être interrogée à partir des points d'entrée commençant par l'url de base http://localhost:8000/api/v1/. Le point d'entrée principal permettant de consulter les films est http://localhost:8000/api/v1/titles.

Les étapes 1 à 6 ne sont requises que pout l'installation initiale. Pour les lancements ultérieurs du serveur de l'API, il suffit d'exécuter les étapes 4 et 7 à partir du répertoire racine du projet.
Utilisation du site
Une fois le serveur virtuel créé, ouvrir la page index.html. Vous devriez voir apparaître le meilleur film ainsi que 4 catégories contenant chacune 7 films dans des listes à faire défiler.
