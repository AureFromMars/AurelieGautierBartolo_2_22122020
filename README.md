# AurelieGautierBartolo_2_22122020
OC P2 Transformer une maquette en site web

Pour faire des retours à la ligne dans un fichier .md Markdown : mettre 2 espaces à la fin de la ligne

Lignes de commandes de base d'un terminal :
>pwd  
>ls  
>ls -la affiche les élements cachés
>cd  replace dans le dossier utilisateur, si suivi d'un paramètre . .. / *, permet d'y rendre
>mv  
>rm  
>touch  
>mkdir  
>spécifier un emplacement  
        . dossier courant  
        .. dossier parent  
        / dossier racine  
        * permet de raccourcir un nom, ex f* pour tous les fichiers commançant par f, et *r pour tous les fichiers finissant par r   
Faire une modif dans un dossier, ajouter le paramètre -r après la commande, comme par exemple rm -r dossier  

Les commandes liées au partage GITHUB sont :  
>git init  
>git clone  
>git add  
>git pull  
>git push  
>git status  
>git branch  
>git checkout  

Pour se repositionner au niveau utilisateur de mes dossier : cd

Ah oui, et bien sûr :  
\> et >>  
notamment avec cat << END >> monfichier.txt pour écrire dans le fichier, mais en concaténant  
cat << END > monfichier.txt pour écrire dans le fichier mais en écrasant les données  
\END permet de clore l'édition du fichier, mais je peux mettre ce que je veux  
et si je veux l'écrire dans le corps du fichier mais sans l'interpréter, il faut mettre devant un "\"  

Pour commiter : git commit -m "Message" et c'est tout !

3 versions locales pour 1 serveur distant :  
> git add "READ ME.md" sert à ajouter mes modifs faites dans la version "working directory" [1] to the version "stage" [2]  
> git commit -m "Message de modif du READ ME" sert à ajouter les modifs faites dans "stage" [2] to the "repository" [3] version  
> git push origine features sert à pousser mes modifs locales sur le serveur distant de GIT HUB [4]  