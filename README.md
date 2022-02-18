# Mon premier repository

## Présentation
Mon premier repository 

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

* Récuperer le repository git
```shell
git clone <url>
```

* Créer une branche 
```shell
git checkout <nom_branche>
```

* Ajouter sa branche 
```shell
git push -u origin <nom_branche>
```

* Voir les branche en local 
```shell
git branch
```

* Voir toutes les branches 
```shell
git pull
git branch -a
```

* changer de branche
```shell
git checkout <nom>
```