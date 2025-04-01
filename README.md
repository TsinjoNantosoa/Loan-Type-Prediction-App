# Application de Prédiction de Type de Prêt

Ce projet est une application web pour prédire les types de prêts en fonction des entrées utilisateur. Il utilise un modèle d'apprentissage automatique pour faire des prédictions et est construit avec Flask.

## Structure du Projet

- `app.py`: Le fichier principal de l'application qui configure le serveur Flask et gère les requêtes de prédiction.
- `loan_prediction_model (1).pkl`: Le modèle d'apprentissage automatique pré-entraîné utilisé pour faire des prédictions.
- `templates/index.html`: Le modèle HTML pour l'interface utilisateur de l'application web.
- `static/`: Répertoire pour les fichiers statiques (par exemple, CSS, JavaScript).

## Installation

1. **Cloner le dépôt :**

   ```bash
   git clone https://github.com/TsinjoNantosoa/Loan-Type-Prediction-App
   cd Loan-Type-Prediction-App
   ```

2. **Créer un environnement virtuel et l'activer :**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Installer les paquets requis :**

   ```bash
   pip install -r requirements.txt
   ```

   *(Remarque : Vous devrez créer un fichier `requirements.txt` avec les dépendances nécessaires, telles que Flask et numpy.)*

## Utilisation

1. **Exécuter l'application :**

   ```bash
   python app.py
   ```

2. **Accéder à l'application :**

   Ouvrez votre navigateur web et allez à `http://127.0.0.1:5000/`.

3. **Faire une prédiction :**

   Entrez les détails requis dans le formulaire et soumettez pour obtenir une prédiction.

## Modèle

Le modèle utilisé dans cette application est un modèle d'apprentissage automatique pré-entraîné stocké dans `loan_prediction_model (1).pkl`. Il prédit les types de prêts en fonction de caractéristiques d'entrée telles que l'état matrimonial, l'historique de crédit et le revenu du coemprunteur.

## Contribution

N'hésitez pas à forker ce dépôt et à soumettre des pull requests. Pour des changements majeurs, veuillez d'abord ouvrir une issue pour discuter de ce que vous souhaitez changer.
