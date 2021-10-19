### TP1
TP1 cour H64

# Comment utiliser le serveur
Build l'image à partir du Dockerfile dans le répertoire
>docker build . -t serveurweb

Run notre serveur web sur le port 8080
>docker run -it --rm -p 8080:80 serveurweb

Ouvrir un navigateur et tapez l'adresse local sur le port :8080 pour acceder au siteweb
>http://localhost:8080


