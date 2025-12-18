🌿 Classification des Maladies des Plantes
📋 Description
Système intelligent combinant vision par ordinateur et modèles de langage (LLM) pour :

Détecter automatiquement les maladies des plantes à partir d'images de feuilles
Fournir des recommandations de traitement organique personnalisées

Ce projet utilise un CNN pour la classification d'images et un LLM pour générer des conseils de traitement adaptés à chaque maladie détectée.
🎯 Objectifs

Classification précise des maladies végétales
Recommandations organiques pour le traitement
Interface intuitive pour les agriculteurs et jardiniers

🛠️ Technologies utilisées

Deep Learning : PyTorch, CNN (Convolutional Neural Networks)
Computer Vision : Traitement et analyse d'images
LLM : Génération de recommandations textuelles
Python : NumPy, Pandas, Matplotlib

🏗️ Architecture du projet
planthealth/
├── data/               # Dataset d'images de plantes
├── models/             # Modèles CNN entraînés
├── notebooks/          # Notebooks Jupyter pour l'exploration
├── src/
│   ├── preprocessing/  # Prétraitement des images
│   ├── training/       # Entraînement du modèle CNN
│   ├── inference/      # Prédiction et classification
│   └── llm_integration/ # Intégration LLM pour 
