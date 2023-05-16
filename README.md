# File Transfer using TCP Socket in Python3
A simple client-server program, where client send a file to server. 


 la fonctionnalité de liste des fichiers hébergés :

Dans le serveur (server.py), vous pouvez ajouter une fonction pour récupérer la liste des fichiers dans le répertoire spécifié dans la configuration du serveur.
Cette fonction doit être appelée lorsque le client envoie une demande "LIST" au serveur.
Le serveur doit envoyer la liste des fichiers hébergés au client.


et gere  les demandes de téléchargement de fichiers :

Dans le serveur (server.py), vous devez ajouter une fonction pour gérer les demandes de téléchargement de fichiers provenant du client.
Lorsque le client envoie une demande "DOWNLOAD filename" au serveur, le serveur doit vérifier si le fichier demandé existe dans le répertoire spécifié.
Si le fichier existe, le serveur doit envoyer le contenu du fichier au client. Sinon, le serveur doit informer le client que le fichier n'a pas été trouvé.

et le cas de   plusieurs clients simultanément :

Actuellement, votre serveur n'est conçu que pour gérer une seule connexion client à la fois.
Pour gérer plusieurs clients simultanément, vous pouvez utiliser des threads ou des processus pour chaque nouvelle connexion client acceptée.
Lorsque le serveur accepte une nouvelle connexion, il doit démarrer un nouveau thread ou processus pour gérer cette connexion tout en restant à l'écoute de nouvelles connexions.# FTU-
# FTU-
