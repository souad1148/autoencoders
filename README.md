Autoencoders – Representation Learning & Denoising

Ce dépôt autoencoders contient des notebooks Jupyter dédiés à l’étude, l’implémentation et l’analyse des autoencoders profonds et des autoencoders convolutionnels de débruitage, utilisés pour l’apprentissage de représentations latentes et la réduction du bruit dans les données.

🎯 Objectifs pédagogiques et techniques

Comprendre le principe fondamental des autoencoders

Étudier l’impact de la profondeur du réseau

Appliquer les autoencoders convolutionnels aux données bruitées

Analyser la qualité de reconstruction

Comparer les performances selon l’architecture utilisée

📁 Notebooks inclus
🔹 01 – Deep Autoencoders

📄 01_deep_autoencoders.ipynb

Contenu :

Autoencoder classique

Architecture Encodeur → Espace latent → Décodeur

Autoencoders profonds

Apprentissage non supervisé

Reconstruction des données

Analyse de l’erreur de reconstruction

🎯 Objectif :
Apprendre une représentation latente compacte des données

🔹 02 – Convolutional Denoising Autoencoders

📄 02_convolutional_denoising_autoencoders.ipynb

Contenu :

Autoencoders convolutionnels (ConvAE)

Ajout de bruit artificiel aux entrées

Apprentissage du débruitage

Rôle des couches convolutionnelles

Comparaison : données bruitées vs reconstruites

🎯 Objectif :
Supprimer le bruit tout en conservant l’information essentielle

🧠 Concepts clés abordés

Autoencoder

Deep Autoencoder

Convolutional Autoencoder

Denoising Autoencoder

Apprentissage non supervisé

Espace latent

Fonction de perte (reconstruction loss)

🛠️ Technologies utilisées

Python 3

Jupyter Notebook

NumPy

Matplotlib

TensorFlow / Keras

scikit-learn

▶️ Exécution des notebooks

Cloner le dépôt :

git clone https://github.com/<votre-username>/autoencoders.git


Installer les dépendances :

pip install numpy matplotlib scikit-learn tensorflow jupyter


Lancer Jupyter Notebook :

jupyter notebook


Ouvrir le notebook souhaité (01_ ou 02_).

📊 Données

Données utilisées à des fins expérimentales et pédagogiques

Bruit ajouté artificiellement pour les expériences de débruitage

Chargement des données directement dans les notebooks

📈 Résultats attendus

Visualisation des données originales

Visualisation des données bruitées

Reconstruction par l’autoencoder

Comparaison qualitative et quantitative

Analyse critique des limites des modèles

👩‍💻 Auteur

Souad Ibaaz
Master Intelligence Artificielle et Applications
📍 Maroc

📧 Email : souadibaaz@gmail.com

🔗 LinkedIn : https://www.linkedin.com/in/souad-ibaaz-508779349/

📌 Remarques

Projet à vocation académique

Accent mis sur la compréhension conceptuelle

Code volontairement clair et structuré

Toute amélioration ou suggestion est bienvenue
