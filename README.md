# Classification of points inside a circle using a neural network

This Python code shows how to build a neural network for classifying points inside a circle using the Scikit-learn library.
How to use this code

1) Install Python and the required libraries (Numpy, Matplotlib, and Scikit-learn).

2) Download the Jupyter Notebook file (.ipynb) containing the code and open it in Jupyter Notebook.

3) Run the code to generate the graphs showing the points and predictions.

## Code content

1) The Python code consists of the following steps:
    - Generating a training and test set for a neural network by creating a matrix of points in a square and labeling them as belonging to one of two classes based on their distance from the center of the square.
    - Displaying a graph that plots the two-dimensional points belonging to the Y=0 and Y=1 groups with different colors.
    - Creating a neural network model with two layers (of 32 and 16 neurons), then separating the data into training and test sets. The model is trained on the training data by recording the loss, and then the evolution of the loss over iterations is plotted and the labels of the test data are predicted.
    - Displaying the predictions of the model on the training data in two dimensions, with green points if the prediction is correct and red points otherwise.
    - Displaying a graph that shows the separation between the two classes using contours.

## Author

This code was written by Pierre-Briac METAYER--MARIOTTI.

# Classification des points à l'intérieur d'un cercle avec un réseau de neurones

Ce code Python montre comment construire un réseau de neurones pour classifier des points à l'intérieur d'un cercle en utilisant la bibliothèque Scikit-learn.
Comment utiliser ce code

1) Installez Python et les bibliothèques nécessaires (Numpy, Matplotlib et Scikit-learn).

2) Téléchargez le fichier Jupyter Notebook (.ipynb) contenant le code et ouvrez-le dans Jupyter Notebook.

3) Exécutez le code pour générer les graphiques montrant les points et les prédictions.

## Contenu du code

1) Le code Python se compose des étapes suivantes :
    - Génération d'un ensemble d'entraînement et de test pour un réseau de neurones en créant une matrice de points dans un carré et en les étiquetant comme appartenant à l'une des deux classes en fonction de leur distance par rapport au centre du carré.
    - Affichage d'un graphique qui trace les points en deux dimensions appartenant aux groupes Y=0 et Y=1 avec des couleurs différentes.
    - Création d'un modèle de réseau de neurones avec deux couches (de 32 et 16 neurones), ensuite on sépare les données en ensembles d'entraînement et de test. On entraîne le modèle sur les données d'entraînement en enregistrant la perte, puis on trace l'évolution de la perte au fil des itérations et on prédit les étiquettes des données de test.
    - Affichage des prédictions du modèle sur les données d'entraînement en deux dimensions, avec des points verts si la prédiction est correcte et des points rouges sinon.
    - Affichage d'un graphique qui montre la séparation entre les deux classes à l'aide des contours.

## Auteur

Ce code a été écrit par Pierre-Briac METAYER--MARIOTTI.
