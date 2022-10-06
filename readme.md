# PasswordGuesser

PasswordGuesser est un projet visant à simuler la création de mots de passe d'utilisateurs sur le web à partir d'informations données. L'idée principale étant de faire prendre conscience aux utilisateur de la faiblesse générale de leurs mots de passe et de la simplicité de piratage qui est en jeu.

## Objectif
L'objectif premier pour ce cours est de pratiquer l'Orienté Objet, sujet initial du cours pour lequel à été réalisé ce projet. Une interface web devra également être réalisée et sera in fine mise en ligne.

## Technos
Par souci de simplicité, les techologies suivantes seront obligatoires : 
- HTML & CSS
- JAVASCRIPT (natif)
- PYTHON (natif)

Le HTML & le CSS seront utilisés pour générer l'interface graphique web utilisateur. L'utilisation d'un template trouvé sur le net est fortement recommandé afin d'obtenir un résultat propre et professionnel.

Le JavaScript ne devra être utilisé qu'en natif, et ne devra avoir aucun framework d'implémenté.

Le code réalisé en Python devra également être natif. Des librairies peuvent être utilisées, mais aucun framework n'est autorisé. L'ensemble du code devra être réalisé en orienté objet uniquement, et le fichier de lancement du script ne devra contenir qu'une seule ligne (éventuellement une de plus pour réaliser un import).

NB : Pour pouvoir exécuter un script python depuis le JavaScript, vous aurez peut-etre besoin d'utiliser un framework ou micro-framework, du type Flask par exemple. Vous pourrez l'implémenter une fois votre programme python 

## interface graphique

L'interface graphique devra présenter un formulaire dynamique à l'utilisateur. Celui-ci pourra : 
- renseigner un nombre de mots illimité (1 mot par champs) ;
- renseigner un nombre de dates illimité (1 date par champs).

Une fois le formulaire soumi, les informations devront être envoyées en asynchrone au programme python, qui réalisera l'ensemble du traitement des données. Ce programme devra donc renvoyer une liste de mots de passe générés à partir des informations fournies au format JSON, de telle sorte que la page web initiale pourra les afficher dans un tableau filtrable (utilisation de DataTables autorisée).

## Options du Guesser

Le formulaire ainsi que le programme devront proposer de choisir parmis plusieurs options pour la génération des mots de passe.

### Options pour les mots
- Basculer toutes les lettres en minuscule
- Basculer toutes les lettres en majuscule
- Basculer la première lettre en majuscule
- Retirer les accents
- Utiliser le L33T pour 1 lettre
- Utiliser le L33T pour plusieurs lettre (toutes les combinaisons avec/sans possibles)
- Utiliser le L33T pour toutes les lettres

### Options pour les dates
- Utiliser les nombres des dates
- Transformer les dates en langage humain

### Options caractères spéciaux
- Ajouter les caractères spéciaux les plus communs (.$?!*)
- Ajouter tous les caractères spéciaux
- Nombre de caractères spéciaux maximums dans la combinaison ?


A FINIR
- Dates
  - séparation des dates ? 
  - dates au format francais ?
  - années (2 chiffres, 4 chiffres ?
- Caractères spéciaux (liste des plus utilisés)

## Groupes
Solo + entraide


## Liens utiles Design Pattern

https://en.wikipedia.org/wiki/Design_Patterns

https://en.wikipedia.org/wiki/Software_design_pattern
