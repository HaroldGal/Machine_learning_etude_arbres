# Analyse Statistiques des espèces d'arbres
Ce répertoire contient les codes d'une approche d'apprentissage statistiques cherchant la prédiction d'espèce d'arbre en fonction des caractéristiques. La base de données se trouve [ICI](https://archive.ics.uci.edu/ml/datasets/Covertype).

## Auteurs

* [Harold Gallice](https://www.linkedin.com/in/harold-gallice-43656212a/)
* [Mohamed Djerrab](https://www.linkedin.com/in/mohamed-djerrab-9a4944167/)


## Prérequis

L'application s'utilise avec python3.
Nous avons utilisé un notebook jupyter pour une meilleure visualisation des résultats.
Il est facile de lancer les scripts en créant un répertoire sur un drive google et en utilisant collaboratory, aucune librarie ne devra être installée.
Si vous voulez faire tourner les scripts en local, pensez à installer les libraries les plus utilisées du machine learning, Keras, TensorFlow, numpy ...

## Organisation

Dans le dossier scripts vous trouverez 3 scripts présentant les principaux résultats.

* **Analyse de donnée** contient toute la phase de visualisation et d'analyse de notre jeu de données.

* Le fichier **BigScore** contient les tests et modèles utilisés pour avoir un grand score globale avec des données random pour entrainement.

* Le fichier **TestScoreHomogène** contient les tests et modèles utilisés afin d'avoir des scores locaux corrects à l'aide d'un bon équilibrage.

Vous trouverez un rapport scolaire présentant les résultats des graphiques dans la partie documentation.
