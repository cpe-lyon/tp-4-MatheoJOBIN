# Exercice 1

1. `sudo apt-get update; sudo apt-get upgrade; sudo apt-get dist-upgrade` permet de mettre à jour le système

2. Il faut l'enregistrer dans le .bashrc, ou activer le .bash_aliases s'il ne l'est pas déjà et les mettre dans ce fichier

3. `cat /var/log/dpkg.log | grep "installed"` permet de voir les derniers paquets installés sur la machine

4. 

5. `dpkg --list | wc --lines; apt list --installed | grep -c 'installed'` permettent d'obtenir le nombre de paquets installés, 

6. 

7. `apt show NOM_PAQUET` permet de voir les informations fournies par les développeurs avant d'installer un paquet

8. `apt search sudoku` permet de chercher tous les paquets ayant le terme sudoku dans le titre ou la description


# Exercice 2

ls est installé à partir de coreutils, la commande `dpkg -S COMMANDE` permet de savoir quel paquet est celui qui a installé la commande.

# Exercice 3

# Exercice 4

# Exercice 5

# Exercice 6

# Exercice 7

# Exercice 8

