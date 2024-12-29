# Reconnaissance de la Langue des Signes avec CNN

Ce projet consiste à construire un modèle de deep learning utilisant un réseau de neurones convolutifs (CNN) pour classifier des signes de la main à partir d'images. Le modèle reconnaît 29 classes, représentant les lettres A-Z, ainsi que "del", "nothing" et "space".

## Principales Fonctionnalités
- **Jeu de Données :** Images de 29 classes de signes, prétraitées et normalisées.
- **Architecture du Modèle :**
  - **CNN personnalisé :** Avec couches convolutionnelles, normalisation batch, dropout, et une couche de sortie softmax.
  - **MobileNetV2 :** Utilisation d'un modèle pré-entraîné comme base pour extraire des caractéristiques avancées, avec un fine-tuning pour s'adapter aux données spécifiques du projet.
- **Entraînement :** Inclut l'augmentation des données, l'arrêt anticipé, et un ajustement dynamique du taux d'apprentissage.
- **Performance :** Environ 95 % de précision sur l'entraînement et 90 % sur la validation.

2. Entraînez le modèle :
   ```bash
   python CNN.ipynb
   ```

Ce projet met en lumière le potentiel du deep learning et de MobileNetV2 pour améliorer la communication pour la communauté malentendante.

