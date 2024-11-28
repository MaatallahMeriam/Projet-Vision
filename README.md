# Modèle de Classification d'Images avec CNN, React et Django

## Description
Ce projet vise à développer un **modèle de classification d'images** en utilisant des **réseaux de neurones convolutifs (CNN)** pour effectuer des prédictions sur des images. L'application web est construite avec un **frontend React.js** et un **backend Django** qui communiquent pour effectuer la classification et afficher les résultats.

Le modèle CNN est entraîné sur un jeu de données d'images et optimisé pour obtenir une précision optimale. Le frontend React permet à l'utilisateur de télécharger des images et d'afficher les résultats de la classification.

## Fonctionnalités
- **Backend avec Django** : API RESTful pour la gestion des requêtes, entraînement du modèle et prédiction des images.
- **Frontend avec React.js** : Interface utilisateur interactive permettant de télécharger des images et d'afficher les résultats de la classification.
- **Réseaux de neurones convolutifs (CNN)** : Utilisation de CNN pour entraîner et effectuer des prédictions sur des images.
- **Optimisation du modèle** : Ajustement des hyperparamètres pour améliorer la précision du modèle.
- **Gestion des erreurs et des validations** : Vérification du format des images avant l'envoi au backend.

## Technologies utilisées
- **Backend** :
  - **Django** (framework Python pour le backend)
  - **Django REST Framework** (pour créer une API RESTful)
  - **TensorFlow** ou **PyTorch** (pour la création et l'entraînement des CNN)
  - **NumPy** et **Pandas** (pour le traitement des données)
  - **OpenCV** ou **Pillow** (pour le traitement des images)

- **Frontend** :
  - **React.js** (bibliothèque JavaScript pour le développement du frontend)
  - **Axios** (pour effectuer des requêtes HTTP vers l'API Django)

## Installation et exécution

### 1. Backend (Django)  
1. Clonez le repository du backend :  
   ```bash
   git clone <URL-du-repository-backend>
