# Récapitulatif des commandes git
## hgestion git en local
- git add.
permet d'ajouter tous les fichiers qui ont été modifié au prochain commit.

- git commit - m "branche/ no_fetaure : message descriptif"
Ajout d'un commit avec son message descriptif.

- git reset
permet de retirer les fichisers à la surveillance de git pour le prochain commit


## gestion de git en remote (GitHub, GitLab..)
- git remote add nom_du_remote https://github.com/slampas/demo-git_idp_ibm
ajout du depot distant

- git push nom_du_remote_branche_local
par exemple :
- git push origin main

il est possible de parametrer la branche pour toujour pousser au meme endroit, ce qui vous permet 
