# Carcinogenicity_Prediction

Description du projet:

![Description de l'image](Hackathon.jpg)

Ce projet vise à prédire la carcinogénicité des composés organiques à partir de leur structure chimique. Il a été réalisé dans le cadre d'un hackathon et constitue une contribution à l'identification rapide des effets toxiques potentiels des nouvelles molécules. Les données utilisées ont été extraites du fichier CSV "Carcinogenicity_Carcinogenicity.csv" de la base de données toxric. Elles contiennent les valeurs de toxicité cancérigène (1 ou 0) de 1021 molécules. Les descripteurs chimiques ont été calculés à partir des formats SMILES en utilisant le module RDKit de Python.

Captures d'écran:
![](cap1)

Méthodologie:

Plusieurs algorithmes de classification binaire ont été utilisés pour construire le modèle de prédiction, notamment la régression logistique, les machines à vecteurs de support (SVM) et les réseaux de neurones artificiels (ANN). Ces algorithmes ont été sélectionnés pour leur capacité à traiter des problèmes de classification et à prédire avec précision la carcinogénicité des composés organiques.


Évaluation des performances:

Les performances des différents modèles ont été évaluées en utilisant des métriques courantes telles que l'exactitude (accuracy), la précision (precision), le rappel (recall) et la courbe ROC. Ces mesures permettent de déterminer l'efficacité du modèle dans la prédiction de la carcinogénicité et de comparer les performances entre les différentes approches.


Données:

Les données utilisées dans ce projet ont été extraites du fichier CSV "Carcinogenicity_Carcinogenicity.csv" de la base de données toxric. Le fichier contient les valeurs de toxicité cancérigène de 1021 molécules. Les descripteurs chimiques nécessaires ont été calculés à partir des formats SMILES à l'aide du module RDKit de Python.
