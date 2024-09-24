branch-b
modif branch-b
=========
modif branch-a
main


1/ créer un dossier de projet  

2/ créer 3 dossiers (html/css/js)

3/ créer les fichiers index.html, index.js et styles.css dans leurs dossiers respectifs

4/ mettre a jour l'ensemble dans le dossier remote

5/ créer une branche "dev"

6/ lister les branches

	-main
	-dev

7/ se positionner sur la branche dev

8/ modifier le fichier css 

9/ mettre la modif a jour sur la branche dev

	commit -a -m "mise à jour dev"

10/ revenir sur la branche master et ouvrir le fichier css (voit-on la modif ?) 

	non

11/ fusionner la branche dev sur la branche master 
	Git merge dev

12/ verifier la modif css

13/ retourner sur la branche dev et ajouter un fichier readme.md

14/ faire un commit de ce fichier 

15/ visualiser les differences avec la commande adéquate

	git diff dev main

16/ créer deux nouvelles branches branch-a et branch-b

17/  dans chaque fichier readme de chaque branche, ajoutez une ligne spécifique (modif branch-a et branch-b par ex)

18/ comparez les deux branches avec la fonction adéquate
 
	git diff branch-a branch-b

19/ mergez la branche a sur master 
	
	Git merge branch-a

20/ mergez la branche b sur master 

	Git merge branch-b

21/ essayez de resoudre le conflit ... 

	Enlever les "<>"
