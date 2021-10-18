# minecraft
```

apt-get update
apt install default-jre
apt install default-jdk
apt install software-properties-common
apt-get update
apt install screen
apt-get install net-tools
apt-get update
```

- Créer un nouveau répertoire qui s’appelle “/home/TP01”
- il faut ensuite installer le “Coeur” du serveur qui s’appelle un spigot, vous pouvez
- installer les dernière version ici et glissez le dans le rep que vous avez créé [paper](https://papermc.io/downloads#Paper-1.16) et
renommer le nom du Spigot en “paper”
- créer un script qui s’appelle “start.sh” et son contenu : https://pastebin.com/B0n89HHJ
- Aller sur la machine et naviguer dans votre répertoire “TP01”
```
cd /home/TP01/
```

8) quand vous êtes dans le répertoire merci de faire cette commande : 
```
 sh start.sh”
```
- Des fichiers vont se créer et ils vont vous demander d’accepter les EULA et pour cela il
faut juste ouvrir le fichier eula.txt et mettre eula=false en eula=true
- Pour activer le mode “CRACK” il faut edit le fichier “server.properties” et mettre
online-mode=true en online-mode=false

refaire la commande
```
“sh start.sh” 
```
et votre serveur de jeux est prêt !
Pour jouer à minecraft sans payer le jeux, vous pouvez télécharger un launcher crack ici :
https://tlauncher.org/en/ et le lancer et suivre les instructions. Pour vous connecter sur votre
serveur, il faut juste aller dans “Multiplayer” et entrer l’adresse IP de votre machine sur
“CONNEXION RAPIDE
