# AurelieGautierBartolo_2_22122020
OC P2 Transformer une maquette en site web

Je rajouterai ici des informations au READ ME  
Pour l'instant, READ ME est à l'état de test  

J'ai appris les lignes de commandes de GIT  
>pwd  
>ls -la  
>cd  
>mv  
>rm  
>touch  
>mkdir  
ainsi que les moyens de me déplacer dans les dossiers . .. / *  
pour faire une modif dans un dossier, ajouter le paramètre -r après la commande, comme par exemple rm -r dossier  

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

Revoir dans quel ordre faire les choses :  
> git add "READ ME.md" sert à ajouter mes modifs à la branche locale  
> git commit -m "Message de modif du READ ME" sert à ...  
> git push origine features sert à pousser mes modifs locales sur le serveur distant  