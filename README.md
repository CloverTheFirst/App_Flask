Application Web pour la gestion des données
Objectif
L'objectif de cette application web est de permettre aux utilisateurs de lire et de modifier les données d'un fichier CSV. Les données sont stockées dans un fichier CSV nommé doc.csv, qui contient les colonnes suivantes :

Dossard
Nom
Prénom
Date de naissance
Bidon
Sac
Tshirt S
Tshirt M
Tshirt L
Tshirt XL
Tshirt XXL
Fonctionnalités
L'application web offre les fonctionnalités suivantes :

Afficher les données : Affiche les données du fichier CSV dans un tableau.
Modifier les données : Permet de modifier les données d'une ligne du fichier CSV.
Installation
Pour installer l'application web, suivez les étapes suivantes :

Clonez le dépôt Git sur votre machine locale :

bash
Copy code
git clone https://github.com/votre-utilisateur/votre-projet.git
Accédez au répertoire du projet :

bash
Copy code
cd votre-projet
Installez les dépendances :

Copy code
npm install
Démarrez l'application :

sql
Copy code
npm start
Ouvrez votre navigateur et accédez à l'URL suivante :

arduino
Copy code
http://localhost:3000
Technologies utilisées
L'application web est développée en JavaScript et utilise les technologies suivantes :

Vue.js : Framework JavaScript pour la création d'interfaces utilisateur.
Bootstrap : Framework CSS pour la création de designs responsives.
Express : Framework JavaScript pour la création de serveurs web.
