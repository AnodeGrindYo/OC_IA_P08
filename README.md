# Projet 8 - Participer à la conception d'une voiture autonome

## Description
Dans le cadre de ce projet de Data Science, je dois participer à la conception d'un système de vision par ordinateur pour des voitures autonomes. Mon rôle consistera à concevoir un modèle de segmentation d'images qui sera intégré dans la chaîne complète du système embarqué. Pour cela, j'utiliserai le jeu de données Cityscapes et utiliserai des techniques d'augmentation de données pour entraîner un modèle de Deep Learning. Je devrai également évaluer le modèle en utilisant des métriques appropriées, comparer un modèle de référence et optimiser les hyperparamètres pour obtenir les meilleures performances possibles. Le modèle est déployé sous la forme d'une API REST

## Objectifs
- Entraîner un modèle de Deep Learning sur des images et évaluer ses performances.
- Utiliser des techniques d'augmentation des données.
- Manipuler un jeu de données volumineux (générateur de données).

## Technologies utilisées
- python
- pandas
- numpy
- matplotlib
- Seaborn
- Scipy
- imgaug
- Tensorflow
- Unet
- VGG16
- cuda
- AWS EC2
- uvicorn


## Compétences évaluées
- Entraîner un modèle de Deep Learning sur des images en identifiant la cible, en séparant le jeu de données en jeu d'entraînement et en jeu de test et en évitant les fuites d'informations.
- Évaluer la performance d'un modèle de Deep Learning sur des images en utilisant des métriques adaptées, en évaluant la performance d'un modèle de référence et en optimisant les hyperparamètres.
- Utiliser des techniques d'augmentation des données en utilisant au moins trois techniques pour améliorer la performance du modèle.
- Manipuler un jeu de données volumineux en développant un générateur de données permettant le traitement des images sur plusieurs cœurs de calcul.