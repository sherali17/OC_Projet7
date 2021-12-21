# OC_Projet7

L'objectif de ce projet est de prédire le risque de faillite d'un client pour un établissement de crédit.
Après la construction d'un modèle de classification, ce dernier est hébergé sur un serveur Flask qui communique via une Api avec un Dashboard interactif élaboré avec Streamlit.

Le Dashboard doit au minimum contenir les fonctionnalités suivantes :
- Permettre de visualiser le score et l’interprétation de ce score pour chaque client de façon intelligible pour une personne non experte en data science.
- Permettre de visualiser des informations descriptives relatives à un client (via un système de filtre).
- Permettre de comparer les informations descriptives relatives à un client à l’ensemble des clients ou à un groupe de clients similaires.

La partie features engineering n'étant pas la partie la plus importante de ce projet, il nous est proposé d'utiliser un Notebook disponible sur le site de Kaggle, dont le lien est disponible au bas de cette présentation.

# Contenu de ce dépôt

- API.py qui est le fichier Flask contenant la partie backend.
- Dasboard.py contient la partie Frontend codée avec Streamlit.
- P7_notebook_V2.ipynb contient le notebook ayant servi à la construction et à l'entrainement du modèle

# Modèle 

Plusieurs modèles de classification ont été utilisés lors de la modélisation. Nous avons retenu le modèle XGBoost pour le fonctionnement de l'application

# Données d'entrée

Lien de téléchargement des données d'entrée : https://www.kaggle.com/c/home-credit-default-risk/data

# Kernel Kaggle ayant servi de base à la modélisation

Notebook de départ pour la partie Features Engineering : https://www.kaggle.com/willkoehrsen/start-here-a-gentle-introduction

