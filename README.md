# NetworkFuzzer-AI-Security

## Description
Ce projet utilise des techniques de machine learning pour analyser du trafic reseau (logs de type AWS VPC Flow) afin de detecter des anomalies liees a des menaces de cybersecurite, classifier le type d'attaque et proposer des pistes de reponse automatisee.

## Objectifs
Le projet vise a detecter les anomalies dans le trafic web, classifier les types d'attaques (DDoS, injection SQL, etc.) et proposer des strategies de reponse automatisees.

## Donnees
Le projet s'appuie sur un jeu de donnees de logs reseau (cleaned_featured_data.csv) contenant notamment des adresses IP source et destination, le protocole, les regles declenchees, le type de detection, l'intensite du trafic et le volume de donnees echangees.

## Technologies utilisees
Python (pandas, numpy), visualisation avec matplotlib, seaborn et plotly, et machine learning avec scikit-learn (RandomForestClassifier).

## Contenu du notebook
Le notebook cybersecurity-advanced-ai-powered.ipynb couvre le chargement et l'exploration des donnees, le nettoyage des donnees (valeurs manquantes, doublons), l'encodage et la normalisation des variables, l'entrainement d'un modele de classification Random Forest, puis l'evaluation du modele via un rapport de classification et une matrice de confusion.

## Auteur
inesmnif
