# 🌸 5 Flower Types Classification using InceptionV3

Projet Deep Learning – Année universitaire 2025/2026  
**Étudiant : Aimad Oufares**

---

## 📘 Description du Projet

Ce projet consiste à développer un modèle de Deep Learning capable de classifier **5 types de fleurs** à partir d'images, en utilisant le **Transfer Learning** avec l'architecture **InceptionV3**.  

L’objectif est de construire une solution complète :

- Exploration du dataset  
- Prétraitement des images  
- Construction et entraînement du modèle baseline  
- Fine-tuning du modèle pour améliorer les performances  
- Évaluation et génération de rapports visuels et textuels  

---

## 📂 Dataset

Le dataset contient environ **4 300 images** réparties en **5 classes** de fleurs :



## 📁 **Structure du Projet**

    flower_images/
            ├── Lilly
            ├── Lotus
            ├── Orchid
            ├── Sunflower
            └── Tulip


- Images équilibrées et de bonne qualité  
- Idéal pour le Transfer Learning  

📎 Source Kaggle : [5 Flower Types Classification Dataset](https://www.kaggle.com/datasets/kausthubkannan/5-flower-types-classification-dataset)

---
------------------------------------------------------------------------

## 🧠 Objectifs d'Apprentissage

- Comprendre et appliquer le **Transfer Learning**  
- Utiliser une architecture avancée (**InceptionV3**)  
- Préparer un pipeline complet de classification d’images  
- Implémenter le **fine-tuning** pour optimiser les performances  
- Évaluer un modèle avec précision, matrice de confusion et rapport de classification  

---

## 🛠️ Technologies Utilisées

- Python 3  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib / Seaborn  
- scikit-learn  
- Google Colab (GPU)  

---

## 📁 Structure du Projet

Flower_Classification_Inception/
                            │
                            ├── code/
                            │ ├── 01_data_exploration.ipynb
                            │ ├── 02_baseline_model.ipynb
                            │ ├── 03_fine_tuning.ipynb
                            │ └── 04_evaluation.ipynb
                            │
                            ├── data/ ← dataset (ignoré dans Git)
                            │ └── .gitkeep
                            ├── models/ ← modèles sauvegardés
                            │ └── inception_finetuned.h5
                            ├── reports/ ← fichiers générés
                            │ ├── baseline_training_history.png
                            │ ├── fine_tuning_history.png
                            │ ├── confusion_matrix.png
                            │ └── classification_report.txt
                            ├── README.md
                            ├── requirements.txt
                            └── .gitignore


## 🚀 **Installation & Exécution**

### 1. Cloner le projet

``` bash
git clone https://github.com/username/Flower_Classification_Inception.git
cd Flower_Classification_Inception
```

### 2. Créer un environnement virtuel

``` bash
python -m venv venv
source venv/bin/activate
```

### 3. Installer les dépendances

``` bash
pip install -r requirements.txt
```

------------------------------------------------------------------------

## 👨‍💻 **Auteur**

**Aimad Oufares**\
Master ISI -- Projet Deep Learning\
Université Cadi Ayyad, Marrakech
