# Documentation du tutos github

## Initialisation du dépot

```bash
git init
git remote add origin SSH_REPO
```

## Rédiger un commit(bonne pratique)

```
Titre du commit

Description de notre commit avec des information sur l'évolution du projet 
```

## Envouyer commit sur un depot distant

```bash
git add .
git commit -m "titre du commit"
git push origin main
```


## Création d'une branche

```bash
git checkout -b name_branche
```
Pour les bonne pratiques on vaa intégrer la notion de revue de code. pour cela on va creer une branche ,faire des modification les envoyer sur le depot distant , puis creer une pull request pour demander une revu de code
