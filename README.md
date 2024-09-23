# Documentation du tuto git et github

## Initialisation du dépot

```bash
    git init
    git remote add origin  SSH_REPO
```

## rediger un commit (bonne pratique)

```
Titre du commit

Description de notre commit avec des informations sur l'evolution de notre projet
```

## Creation d'une branche

```bash
git checkout -b NOM_BRANCHE
```

Pour les bonne pratique, on va intégrer la notion de revue de code. Pour cela,
on va créer une branche, faire des modifications, les evoyer sur le dépôt distant,
puis créer un pull request pour demander une revue de code