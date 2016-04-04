# Guidelines
Les lignes de conduites à adopter lors de la contribution à un dépot de cette organisation.

## Contribuer
1. Créez un fork du dépot auquel vous voulez contribuer.
2. Sur votre copie du dépot, créez une branche dont le nom reflète explicitement le but de votre modification.
3. Faites vos modifications sur cette branche, commitez, et poussez les modifications.
4. Une fois la modification terminée, créez une pull request vers le dépot original. Votre modification sera inspectée et intégrée au dépot orignal si elle convient.

## Conventions
- Chaque dépot correspondant à un cours contient:
    - Un dossier résumés dont les sous-dossiers sont les différents résumés disponibles.
    - Un dossier notes dont les sous-dossiers sont les différentes notes disponibles.
- Chaque note ou résumé est compilable en utilisant un Makefile.

## Licences
Une licence de type open-source doit être utilisée. De préférence GPLv3.

Veillez à ce que les synthèses/notes que vous ajoutez vous appartiennent ou que vous disposez d'un autorisation de l'auteur.

## Todo
- Mettre en place un système d'intégration continue serait intéressant. [Travis](https://travis-ci.com) permet d'exécuter la compilation des fichiers tex à chaque push et de créer une release automatiquement avec le pdf généré en ajoutant un message (par exemple celui du commit). Ce système permettrait d'éviter d'alourdir les dépots git pour ceux qui ne veulent que contribuer et de n'avoir qu'à télécharger le dernier pdf généré, sans devoir cloner le dépot, pour ceux qui ne veulent que le pdf.
La structure et les conventions sont alors essentielles pour qu'on puisse facilement installer l'intégration continue dans chaque dépot.
