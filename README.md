# CARONCH

Jean-Pierre Prunaret  Yves Dubromelle


v0.1

# Résumé

Présentation du formalisme CARONCH, Carré-Rond-Flèche.
Un formalisme simple permettant de monter les processus et les données d'un système.

# Objectifs

CARONCH pour Carré - Rond - Flèche est un formalisme simple permettant de monter les processus et les données d'un système.

L'objectif principal de ce formalisme est de mettre en valeur les données et les interactions autour.

# Représentation graphique

* Symboles

  * ![symbole donnée](https://raw.githubusercontent.com/Taeradan/Caronch/master/images/data.png) correspond à une donnée.

  * <Fichier graphique : /home/taeradan/GIT/caronch/formalisme/process.dot>
     correspond à un processus.

* Interactions

  * <Fichier graphique : /home/taeradan/GIT/caronch/formalisme/read_arrow.dot>
     correspond à la lecture d'une donnée par un processus.

  * <Fichier graphique : /home/taeradan/GIT/caronch/formalisme/write_arrow.dot>
    correspond à l'écriture d'une donnée par un processus.

# Règles de construction

1. Les interactions ne sont pas considérées comme des symboles.

2. Le temps n'est pas représenté.

3. L’occurrence des interactions n'est pas représentée.

4. Il y a alternance entre processus et données.

  * Il ne peut y avoir deux (2) symboles identiques à la chaîne.

5. Les étiquettes des symboles doivent être différents s'il 
  caractérisent des informations différentes.

6. Il est possible de regrouper des symboles pour les agréger en 
  un processus de traitement de données.

