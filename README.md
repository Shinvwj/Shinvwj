_**SAE "installer un système"**_
_Principe_
**Nous allons voir comment configurer un système autre que Windows.Dans notre cas, on parlera de XUbuntu avec Linux. Pour cela, nous avons deux solutions:**
- Faire un Dual Boot
- Avoir une VM Virtual box

Nous allons aussi voir comment installer des applications sur ce système. Tout d'abord, il faut savoir quels sont les avantages et les inconvénient des deux manières.
Les avantages du Dual Boot est que nous avons le système directement sur notre ordinateur et que l'on peut continuer d'utiliser Windows.
L'inconvénient à ceci cependant et qu'a chaque redémarrage de l'ordinateur, il faudra sélectionner quel système l'on veut lancer. L'autre inconvénient et que nous ne pouvons pas lancer Windows et XUbuntu en même temps.

**Dual Boot**
Tout d'abord, dans un premier temps, il faut installer le BIOS XUbuntu. Pour l'installer, vous pourrez le faire sur votre navigateur internet. Il sera utile pour les deux solutions.
Pour faire le Dual Boot, Il vous faudra une clé USB, elle est vraiment très importante. Ce qu'on va faire est de faire de cette clé USB une clé bootable. C'est-à-dire que cette clé va nous servir à installer un système d'exploitation.
Il faudra noter que pour cela, il faudra formater la clé USB avant. Ensuite, nous allons utiliser une application au nom de Rufus qui sert justement à faire d'une clé USB, une clé USB bootable. pour cela il faut ouvrir rufus, selectionner le l'IOS, soit Ubuntu ou bien XUbuntu.
ensuite, il faut sélectionner démarrer puis il faut attendre. Il est écrit qu'il faudra écraser la mémoire. N'oublié pas qu'il faut que cette clé soit vide, si vous avez des fichiers importants, il est conseiller de les mettre sur une autre clé.
Ensuite il faut éteindre l'ordinateur afin d'accéder au BIOS. Pour y accéder, cela dépends de votre model d'ordinateur. N'hésitez pas à chercher en fonction de la marque mais surtout le modèle. Une fois le BIOS accéder, il faudra changer l'ordre de priorité du boot et mettre celle de la clé en haut.
Ensuite lorsque cela est fait, on vous demande d'installer XUbuntu. Faites-le puis attendez. Et voilà, Le système est configuré sur l'ordinateur !

**VM Virtual box**
L'avantage du virtual boot lui est de pouvoir faire fonctionner plusieurs système d'exploitation.
Pour faire la Virtual Box, nous  auront aussi besoin de IOS Ubuntu ou XUbuntu. Il faut télécharger le fichier. Il faudra aussi télécharger la VM virtual box
Lorsque cela est fait, il faut ensuite ouvrir la VM. Nous allons créer la machine virtuelle et la configurer, c'est à dire gérer la place que prendra la machine eter t répartir la place en fonction de la RAM et de la taille du disque dur. Tout d'abord, il faut cliquer sur Nouvelle dans la barre d'icône, puis il faut ensuite ajouter l'IOS en parcourant les dossiers et trouver le fichier. Ensuite il faut répartir la place que va prendre la machine sur le système. 
Ensuite, il va falloir choisir la langue ainsi que choisir si l'on veut télécharger Ubuntu/XUbuntu ou alors l'essayer. Il faudra le télécharger. Le chargement risque peut-être d'être long. 

**Installations**
Nous allons voir quels sont les différente commande pour installer Dockers, Python et VScode.
Dockers : sudo apt install docker
VScode : sudo  install --classic code
Python : sudo apt update 
         sudo apt install python3

Voilà pour l'installation et la configuration du système Ubuntu ou XUbuntu
