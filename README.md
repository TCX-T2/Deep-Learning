# Deep-Learning
1/- Repository Strcturation 
medical-image-analysis/
|-- data/                     # Dossier pour stocker les ensembles de données
|   |-- raw/                  # Ensembles de données bruts téléchargés depuis Kaggle, Medical Decathlon, etc.
|   |-- processed/            # Ensembles de données après prétraitement
|   |-- splits/               # Division des données en ensembles d'entraînement, de validation et de test
|
|-- notebooks/                # Notebooks Jupyter pour l'exploration des données, l'entraînement, etc.
|   |-- data_exploration.ipynb
|   |-- model_training.ipynb
|   |-- evaluation.ipynb
|
|-- src/                      # Code source pour la partie deep learning
|   |-- data_preprocessing/   # Scripts ou modules pour le prétraitement des données
|   |-- model/                # Scripts ou modules pour la définition et l'entraînement du modèle
|   |-- evaluation/           # Scripts ou modules pour l'évaluation du modèle
|   |-- utils/                # Utilitaires généraux, par exemple, des fonctions d'aide
|
|-- model/                    # Dossier pour stocker les modèles entraînés
|   |-- model_weights.h5
|
|-- reports/                  # Rapports générés automatiquement sur les résultats
|   |-- detection_report.txt
|   |-- segmentation_report.txt
|
|-- requirements.txt          # Fichier pour les dépendances Python
|-- README.md                 # Documentation sur le projet et son utilisation
