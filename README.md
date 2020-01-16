
cd

    Équivalent MS-DOS/MS Windows : cd
    Signification : change directory
    Permet de se promener dans les répertoires
    Exemples d'utilisation :
        cd
        permet de revenir au répertoire /home/utilisateur (identique à cd ~)
        cd -
        permet de revenir au répertoire précedent
        cd ..
        permet de remonter au répertoire parent (ne pas oublier l'espace contrairement à windows)
        cd /
        permet de remonter à la racine de l'ensemble du système de fichiers
        cd /usr/bin/
        se place dans le répertoire /usr/bin/



pwd

    Équivalent MS-DOS/MS Windows : chdir
    Signification : print working directory
    Affiche le répertoire de travail



ls

    Équivalent MS-DOS/MS Windows : dir
    Signification : list segment
    Permet de lister un répertoire
    Options les plus fréquentes :
        -l : Permet un affichage détaillé du répertoire (permissions d'accès, le nombre de liens physiques, le nom du propriétaire et du groupe, la taille en octets, et l'horodatage)
        -h : Associé avec -l affiche la taille des fichiers avec un suffixe correspondant à l'unité (K, M, G)
        -a : Permet l'affichage des fichiers et répertoires cachés (ceux qui commencent par un . (point))
        -lct : Permet de trier les fichiers et répertoires par date de modification décroissante
    Exemples d'utilisation :
        ls -a
        affiche tous les fichiers et répertoires y compris les cachés du répertoire courant
        ls /etc/
        affiche le contenu du répertoire /etc/
        lspci ou lsusb
        affiche les périphériques PCI ou USB connectés.
        lshw affiche les caractéristiques de tout le matériel physique, non-logiciel (hardware).
    ls en couleur



mkdir

    Équivalent MS-DOS/MS Windows : mkdir ou md
    Signification : make directory
    Crée un répertoire vide
    Options les plus fréquentes :
        -p : Crée les répertoires parents s'ils n'existent pas
    Exemples d'utilisation :
        mkdir photos
        Crée le répertoire photos
        mkdir -p photos/2005/noel
        Crée le répertoire noel et s'ils n'existent pas les répertoires 2005 et photos



rmdir

    Équivalent MS-DOS/MS Windows : rmdir ou rd
    Signification : remove directory
    Supprime un répertoire (vide)
    Options les plus fréquentes :
        -p : Supprime les répertoires parents s'ils deviennent vides
    Exemples d'utilisation :
        rmdir LeRep
        Supprime le répertoire LeRep



rm
Attention cette commande est très dangereuse (voir commandes dangereuses). Exécutez-la uniquement si vous savez ce que vous faites !

    Équivalent MS-DOS/MS Windows : del ou erase
    Signification : remove
    Permet d'effacer des fichiers
    Options les plus fréquentes :
        -i : Demande confirmation avant d'effacer
        -f : Ne demande pas de confirmation avant d'effacer
        -r : Efface récursivement. Ce mot signifie "y compris ses sous-répertoires et leur contenu".
    Exemples d'utilisation :
        rm CeFichier
        Efface du répertoire courant le fichier CeFichier.
        rm -rf /tmp/LeRep
        Efface le répertoire /tmp/LeRep ainsi que tous ses fichiers, liens et sous-répertoires sans demander de confirmation.
        rm -rf /*
        …La commande qui "tue"… Disparition immédiate de tous vos fichiers.


