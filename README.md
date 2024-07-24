### Classification Automatique de Biens de Consommation - Deep Learning

#### Description
Ce projet explore la création d'un moteur de classification automatique pour des articles de consommation, tels que ceux postés par des vendeurs sur une marketplace e-commerce. L'étude se concentre sur la classification basée sur des descriptions textuelles et des images de produits, en utilisant des techniques avancées de deep learning.

#### Contenu
- **Objectif**: Étudier la faisabilité d'un moteur de classification basé sur les descriptions textuelles et les images des produits.
- **Données**:
  - Dataset contenant 1050 produits répartis en 7 catégories avec des descriptions, noms d'images et catégories.
  - Dossier contenant les images des produits.

#### Méthodologie
1. **Nettoyage et Prétraitement des Données**:
   - Normalisation des textes (suppression de ponctuations, conversion en minuscules, suppression des stopwords, etc.).
   - Exploration des données pour comprendre la richesse du vocabulaire et les distributions de taille de documents par catégorie.
   - Utilisation de techniques comme Bag of Words, TF-IDF, et des modèles pré-entraînés tels que Word2Vec, BERT, et USE pour l'extraction des features.

2. **Modèles de Classification pour les Descriptions Textuelles**:
   - Utilisation de différentes techniques de vectorisation des textes pour capturer les relations sémantiques.
   - Évaluation des performances des modèles par rapport aux catégories réelles.

3. **Classification Basée sur les Images**:
   - Prétraitement des images incluant la réduction du bruit et la normalisation.
   - Extraction de caractéristiques avec des méthodes comme SIFT et VGG16.
   - Augmentation des données pour améliorer la robustesse des modèles.

4. **Entraînement et Évaluation des Modèles**:
   - Entraînement de modèles CNN avec des architectures telles que VGG16, DenseNet121, et Xception.
   - Comparaison des performances des modèles avec et sans augmentation de données.

5. **Collecte de Données via API**:
   - Exploration de l'élargissement de la gamme de produits par la collecte de données via des API.

#### Résultats et Conclusion
- Les résultats montrent une bonne performance pour la classification basée sur les descriptions textuelles et les images, avec des modèles comme VGG16 et DenseNet121 affichant des précisions élevées.
- Le projet démontre la faisabilité de créer un moteur de classification automatique pour une marketplace, avec des perspectives d'amélioration pour certaines catégories.

## Auteur
- **Fathi METALSI**
  - [LinkedIn](https://www.linkedin.com/in/fathi-metalsi-328159124/)
  - [Email](mailto:fathimetalsi@gmail.com)