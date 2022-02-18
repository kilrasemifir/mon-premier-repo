# Mon premier repository

## Présentation
git commit : pour save son travail
pit push : quand on se leve de sa chaise

## Instruction pour l'installation
* Pour créer un repository local en git, tapez la commande suivante:
```shell
git init
```

* Pour voir les derniere modification non sauvegardés
```shell
git status
```

* Pour ajouter un fichier a un future commit
```shell
git add <fichier>
```

* Pour sauvegarder les modifications ajouté dans un commit:
```shell
git commit -m <description>
```

* Le fichier `.gitignore`permet a git de connaitre les fichiers et dossiers à ignorer.

* Pour lier le repository local au distant
```shell
git remote add origin <url https du repository distant>
```

* Pousser les commits
```shell
git push origin master
```

<<<<<<< HEAD
Coucou c'est François je modifie
=======
* Récuperer le repository git
```shell
git clone <url>
```
>>>>>>> 3ca15b3d14d86ebc041e6cac1b8f0eab8bc2cf21
