#Documentation du tuto github avec git

##initialiser un depot

```bash
git init
git remote add origin git@github.com:ariss190504/git_tuto.git
```

##Rediger un commit

```
Titre du commit

Description de notre commit avec des informations sur l'evolution du projet 
```

##Envoyer un commit sur le depot distant

```bash
git add .
git commit -m "Titre du commit"
git push origin main
```

##creation d'une nouvelle branche

```bash
git checkout -b NOM_BRANCHE
```
