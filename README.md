# Mon premier repository

## Présentation

C'est le cours de git
=======
## Instruction pour l'installation
* Pour créer un repository local en git, tapez la commande suivante:
```shell
git init
```

* Pour voir les derniere modification non sauvegardés
```shell
git statusdadsadsadsa
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


* récuperer le code depuis github
```shell
git clone https://github.com/kilrasemifir/mon-premier-repo.git
```

* créer une nouvelle branche
```shell
git checkout -b "name"
```

* Changer de  branche
```shell
git checkout "name"
```