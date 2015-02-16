# CARONCH

![Logo Caronch](https://raw.githubusercontent.com/Taeradan/Caronch/master/images/logo.png)

Jean-Pierre Prunaret et Yves Dubromelle


## Résumé

CARONCH, pour Carré-Rond-Flèche est un formalisme simple permettant de monter les processus et les données d'un système.

## Objectifs

Le formalisme CARONCH a été créé pour :

* mettre en valeur les données et les interactions autour
* être simple = peu de symboles différents
* être visuel = utilisation de schéma
* séparer les données et les actions

Les actions sont par exempe : stockage, transformation, suppression, ...

## Représentation graphique

* Symboles

    * une donnée :

        ![symbole donnée](https://raw.githubusercontent.com/Taeradan/Caronch/master/images/data.png)

    * un processus :

        ![symbole processus](https://raw.githubusercontent.com/Taeradan/Caronch/master/images/process.png)

* Interactions

    * lecture d'une donnée par un processus :

        ![symbole processus](https://raw.githubusercontent.com/Taeradan/Caronch/master/images/read_arrow.png)

    * écriture d'une donnée par un processus :

        ![symbole processus](https://raw.githubusercontent.com/Taeradan/Caronch/master/images/write_arrow.png)

## Règles de construction

1. Les interactions ne sont pas considérées comme des symboles.
1. Le temps n'est pas représenté.
1. L’occurrence des interactions n'est pas représentée.
1. Il y a alternance entre processus et données.
1. Il ne peut y avoir deux (2) symboles identiques à la chaîne.
1. Les étiquettes des symboles doivent être différents s'il caractérisent des informations différentes.
1. Il est possible de regrouper des symboles pour les agréger en un processus de traitement de données.

## Licence

![logo creative common by-sa 3.0](http://i.creativecommons.org/l/by-sa/3.0/88x31.png)
[Creative Commons Paternité – Partage à l’Identique 3.0 non transcrit](http://creativecommons.org/licenses/by-sa/3.0/)

