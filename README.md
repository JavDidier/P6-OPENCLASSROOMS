# P6-OPENCLASSROOMS

**INSTALLATION BACKEND**
* - SI téléchargement par GITHUB :
* Créez un dossier vide à la racine de votre projet (par exemple: backend)
* Depuis un terminal à partir du répertoire de travail faites, *git clone https://github.com/JavDidier/P6-OPENCLASSROOMS.git backend* 

* - SI installation par dossier :
* Placer le dossier (backend) et son contenu à la racine de votre projet 
* Créez un fichier *.env* dans le dossier *configs* ( Si nécessaire, se référer au dossier .envExample )
* Et y coller le texte suivant :  


* PORT=3000  
* DB_CONNECT=P6openclassrooms:test654987@p6api.5yjcgal.mongodb.net
* KEY_SECRET=MY_KEY_SECRET  


* Installer NodeJs et les dépendances nécessaires au projet :  

Depuis un terminal à partir du dossier backend (faire *cd backend si necessaire*), faites un *npm install*

* Nodemon est installé pour les besoins du développement
* Depuis votre terminal à partir du dossier backend, faites "npm start" > ceci lance le serveur avec Nodemon


**INSTALLATION FRONTEND - RAPPEL**

* Pour l'installation du frontend, veuillez retrouver le contenu et suivre la procédure sur : 
* https://github.com/OpenClassrooms-Student-Center/Web-Developer-P6


**NOTE IMPORTANTE**

* Le dossier (images) se créer automatiquement au lancement du serveur backend si il n'existe pas.


**Mise à jour le 17/10/2022 par Javierre Didier - Formation OpenClassrooms**