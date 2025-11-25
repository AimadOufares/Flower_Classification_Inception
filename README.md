# 🌸 Classification de 5 Types de Fleurs avec InceptionV3

**Projet Deep Learning – Année universitaire 2025/2026**  
**Auteur : Aimad Oufares**  
**Master ISI – Université Cadi Ayyad, Marrakech**

---

## 📘 Description du Projet

Ce projet a pour objectif de développer un modèle de **Deep Learning** capable de classifier **5 types de fleurs** à partir d’images, en utilisant le **Transfer Learning** avec l’architecture **InceptionV3**.  

Le projet couvre un pipeline complet de classification d’images :

1. **Exploration et analyse du dataset**  
2. **Prétraitement des images et génération de données augmentées**  
3. **Construction et entraînement d’un modèle baseline**  
4. **Fine-tuning du modèle pour améliorer les performances**  
5. **Évaluation et génération de rapports visuels et textuels**  

---

## 📂 Dataset

Le dataset contient environ **5 000 images** réparties en **5 classes** de fleurs :

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

## 🧠 Objectifs d'Apprentissage

- Comprendre et appliquer le **Transfer Learning**  
- Utiliser une architecture avancée (**InceptionV3**)  
- Préparer un pipeline complet de classification d’images  
- Implémenter le **fine-tuning** pour optimiser les performances  
- Évaluer un modèle avec précision, matrice de confusion et rapport de classification  
- Visualiser les résultats et comparer baseline vs fine-tuning  

---

## 🛠️ Technologies Utilisées

- **Python 3**  
- **TensorFlow / Keras**  
- **NumPy, Pandas**  
- **Matplotlib / Seaborn**  
- **scikit-learn**  
- **Google Colab (GPU recommandé)**  

---

## 📁 Structure du Projet

```

Flower_Classification_Inception/
│
├── code/
│   ├── 01_data_exploration.ipynb   # Analyse et visualisation du dataset
│   ├── 02_baseline_model.ipynb     # Entraînement du modèle baseline
│   ├── 03_fine_tuning.ipynb        # Fine-tuning du modèle
│   └── 04_evaluation.ipynb         # Évaluation et génération de rapports
│
├── data/                            # Dataset (ignoré dans Git)
│   └── .gitkeep
├── models/                          # Modèles sauvegardés
│   ├── inception_baseline.h5
│   └── inception_finetuned.h5
├── reports/                         # Graphiques et rapports
│   ├── baseline_training_history.png
│   ├── fine_tuning_history.png
│   ├── compare_histories.png
│   ├── confusion_matrix.png
│   └── classification_report.txt
├── README.md
├── requirements.txt
└── .gitignore

````
---

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


## 📊 Résultats attendus

* Graphiques d’apprentissage (accuracy & loss) pour baseline et fine-tuning
* Matrice de confusion et rapport de classification (Precision, Recall, F1-score)
* Comparaison des performances baseline vs fine-tuning

---

## 💡 Améliorations possibles

* Utiliser un **dataset plus grand** pour une meilleure généralisation
* Expérimenter avec d’autres architectures pré-entraînées (ResNet, MobileNet, VGG)
* Implémenter **EarlyStopping** et **ReduceLROnPlateau** pour optimiser l’entraînement
* Techniques avancées de **data augmentation**

---

## 👨‍💻 Auteur

**Aimad Oufares**
Master ISI – Université Cadi Ayyad, Marrakech
Projet Deep Learning – 2025/2026
