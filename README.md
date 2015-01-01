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

    * une donnée :

![symbole donnée](https://raw.githubusercontent.com/Taeradan/Caronch/master/images/data.png)

    * un processus :

![symbole processus](https://raw.githubusercontent.com/Taeradan/Caronch/master/images/process.png)

* Interactions

  * lecture d'une donnée par un processus :

![symbole processus](https://raw.githubusercontent.com/Taeradan/Caronch/master/images/read_arrow.png)

    * écriture d'une donnée par un processus :

![symbole processus](https://raw.githubusercontent.com/Taeradan/Caronch/master/images/write_arrow.png)

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

