# Guide de contribution

Merci de contribuer à ce projet ! Voici les règles à suivre.

## Workflow

1. Choisissez ou créez une *issue* et assignez-la-vous.
2. Créez une branche à partir de `main` : `feature/nom-court`,
   `fix/nom-court` ou `docs/nom-court`.
3. Faites des commits atomiques, avec des messages au format
   `type: résumé` (`feat`, `fix`, `docs`, `chore`).
4. Poussez votre branche et ouvrez une *pull request* vers `main`.
5. Attendez la revue d'au moins une personne. Corrigez ses remarques
   par de nouveaux commits.
6. Une fois approuvée, la pull request est fusionnée par son auteur.

## Règles

- Ne poussez jamais directement sur `main`.
- Une pull request = un sujet, de préférence moins de 300 lignes.
- Ne committez jamais de mot de passe, de clé ou de fichier `.env`.
- Le programme doit s'exécuter avant toute demande de revue :
  `python -m bibliotheque.main`.

## Signaler un problème

Ouvrez une issue en décrivant le comportement attendu, le comportement
observé et les étapes pour le reproduire.
