# arbre_de_decision

Voici un résumé des principales étapes effectuées dans le script :

## Lecture de la Dataset : 
Utilisation de Pandas pour lire les données à partir du fichier "penguins_size.csv".

## Description de la Dataset : 
Présentation des principales caractéristiques de la dataset, notamment les variables telles que l'espèce, la longueur du culmen, la profondeur du culmen, la longueur de la nageoire, la masse corporelle, l'île et le sexe.

## Vérification des Données Manquantes : 
Utilisation de Pandas pour vérifier et afficher les données manquantes dans la dataset.
## Suppression des Données Manquantes : 
Suppression des lignes contenant des données manquantes en raison de leur proportion.
## Vérification des Types d'Espèces et du Sexe : 
Examen des valeurs uniques pour les espèces et le sexe, identification d'une valeur incohérente ('.') pour le sexe, analyse pour déterminer le sexe correct.
## Observation de la Dispersion des Données : 
Utilisation de Seaborn pour créer des graphiques de dispersion en fonction du type de pingouin.
## Transformation des Données Catégorielles :
Conversion des variables catégorielles (île et sexe) en variables dummies.
## Entraînement et Test du Modèle :
Utilisation de Scikit-Learn pour diviser les données en ensembles d'entraînement et de test, création et ajustement d'un modèle d'arbre de décision.
## Prédiction et Évaluation de la Performance : 
Prédiction des espèces sur l'ensemble de test, utilisation de classification_report et ConfusionMatrixDisplay pour évaluer la performance du modèle.
## Visualisation de l'Arbre de Décision : 
Utilisation de la bibliothèque Scikit-Learn pour afficher graphiquement la structure de l'arbre de décision.
