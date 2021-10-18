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

JAVA 16
```
wget --no-check-certificate -c --header  
wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie" 
https://www.oracle.com/java/technologies/javase/jdk16-archive-downloads.html
```
- Créer un nouveau répertoire qui s’appelle “/home/TP01”
- il faut ensuite installer le “Coeur” du serveur qui s’appelle un spigot, vous pouvez
- installer les dernière version ici et glissez le dans le rep que vous avez créé [paper](https://papermc.io/downloads#Paper-1.16)
https://papermc.io/api/v2/projects/paper/versions/1.17.1/builds/336/downloads/paper-1.17.1-336.jar
-   et
renommer le nom du Spigot en “paper”
- créer un script qui s’appelle “start.sh” et son contenu : https://pastebin.com/B0n89HHJ
- Aller sur la machine et naviguer dans votre répertoire “TP01”
```
cd /home/TP01/
```
quand vous êtes dans le répertoire merci de faire cette commande : 
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


    1  sudo apt-get update
    2  su sti2d
    3  sudo apt-get update
    4  exit
    5  clear
    6  sudo apt-get update
    7  sudo apt-get install default-jre
    8  sudo apt-get install default-jdk
    9  sudo apt-get install software-properties-common 
   10  sudo apt-get install screen
   11  sudo apt-get install net-tools 
   12  sudo mkdir /home/TP01
   13  cd /home/TP01/
   14  wget https://papermc.io/downloads
   15  wget https://papermc.io/api/v2/projects/paper/versions/1.17.1/builds/336/downloads/paper-1.17.1-336.jar
   16  sudo wget https://papermc.io/api/v2/projects/paper/versions/1.17.1/builds/336/downloads/paper-1.17.1-336.jar
   17  ls
   18  mv paper-1.17.1-336.jar paper
   19  sudo mv paper-1.17.1-336.jar paper
   20  ls
   21  sudo nano start.sh
   22  sudo cat start.sh
   23  sudo chmod +x start.sh 
   24  sudo sh  start.sh 
   25  sudo mv paper paper.jar
   26  sudo sh  start.sh 
   27  java -version 
   28  sudo add-apt-repository ppa:linuxuprising/java
   29  sudo apt-get install oracle-java16-installer 
   30  clear
   31  wget https://www.oracle.com/java/technologies/javase/jdk16-archive-downloads.html#license-lightbox
   32  wget https://download.oracle.com/otn/java/jdk/16.0.1%2B9/7147401fd7354114ac51ef3e1328291f/jdk-16.0.1_linux-x64_bin.deb
   33  ls
   34  sudo dpkg -i jdk-16.0.1_linux-x64_bin.deb 
   35  ls
   36  wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie"  https://download.oracle.com/otn/java/jdk/16.0.1%2B9/7147401fd7354114ac51ef3e1328291f/jdk-16.0.1_linux-x64_bin.deb
   37  ls -l
   38  sudo apt-get install lynx
   39  lynx https://www.oracle.com/java/technologies/javase/jdk16-archive-downloads.html
   40  ls
   41  wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie"  https://download.oracle.com/otn/java/jdk/16.0.1%2B9/7147401fd7354114ac51ef3e1328291f/jdk-16.0.1_linux-x64_bin.deb
   42  ifconfig
   43  clear
   44  wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie"  https://download.oracle.com/otn/java/jdk/16.0.1%2B9/7147401fd7354114ac51ef3e1328291f/jdk-16.0.1_linux-x64_bin.deb
   45  ls -l
   46  wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie"  https://download.oracle.com/otn/java/jdk/16.0.1%2B9/7147401fd7354114ac51ef3e1328291f/jdk-16.0.1_linux-x64_bin.deb
   47  rm jdk-16.0.1_linux-x64_bin.deb 
   48  wget --no-check-certificate -c --header "Cookie: oraclelicense=accept-securebackup-cookie"  https://download.oracle.com/otn/java/jdk/16.0.1%2B9/7147401fd7354114ac51ef3e1328291f/jdk-16.0.1_linux-x64_bin.deb
   49* 
   50  java -version
   51  sudo dpkg -i jdk-16.0.1_linux-x64_bin.deb 
   52  sudo apt-get install oracle-java16-installer 
   53  sudo apt-get remove default-jre 
   54  sudo apt-get remove default-jdk
   55  java -version
   56  javac -version
   57  sudo apt-get install oracle-java16-set-default 
   58  java -version
   59  javac -version
   60  cd /home/TP01/
   61  sudo sh start.sh 
   62  sudo nano eula.txt 
   63  sudo nano server.properties 
   64  sudo sh start.sh 
   65  ifconfig
   66  history
