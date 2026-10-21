# 🧠 Réseaux de neurones - De la régression au NLP

[![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.21-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![uv](https://img.shields.io/badge/uv-package%20manager-6E56CF?logo=python&logoColor=white)](https://docs.astral.sh/uv/)
[![Projet académique](https://img.shields.io/badge/Projet-académique-8A2BE2?logo=academia&logoColor=white)]()

Sept ateliers pour constituer une base de savoir-faire en deep learning, de la régression au traitement du langage naturel, complétés par un cas pratique traité seul : comparer un réseau à une méthode simple et conclure avec une marge d'incertitude.

---

## 📚 Contenu

### Travaux pratiques

| TP | Thème | Concepts clés |
|:---|:---|:---|
| **TP1** | [Régression](notebooks/tp1_regression.ipynb) | Réseau de neurones, MSE, R², sous/surapprentissage |
| **TP2** | [Classification binaire](notebooks/tp2_classification_binaire.ipynb) | Sigmoïde, cross-entropy, seuil de décision, précision/rappel |
| **TP3** | [Classification multiclasse](notebooks/tp3_multiclasses.ipynb) | Softmax, sparse categorical cross-entropy, 10 classes |
| **TP4** | [Réseaux convolutifs (CNN)](notebooks/tp4_cnn.ipynb) | Convolution, pooling, images 2D vs aplaties |
| **TP5** | [Régularisation](notebooks/tp5_regularisation.ipynb) | Dropout, L2, early stopping, marge de bruit, multi-graines |
| **TP6** | [Hyperparamètres et compression](notebooks/tp6_hyperparametres_compression.ipynb) | Keras Tuner, validation, pruning, quantification TFLite |
| **TP7** | [NLP - Préparation du texte](notebooks/tp7_texte_nlp.ipynb) | Tokenisation, NLTK, spaCy, vectorisation, classification de texte |

### 🎯 Défi final

[**Défi Moons**](notebooks/defi_moons_romain.ipynb) : Mise en situation pour un client (Datalys) : comparer un réseau de neurones à une régression logistique sur des données non linéairement séparables (`make_moons`), en respectant une rigueur scientifique (marge de bruit, multi-graines, métriques variées).

---

## 🛠️ Stack technique

- **Langage** : Python 3.13
- **Deep Learning** : TensorFlow 2.21 / Keras
- **Machine Learning** : scikit-learn
- **Data** : NumPy, Pandas
- **Visualisation** : Matplotlib
- **NLP** : NLTK, spaCy
- **Optimisation** : Keras Tuner
- **Gestionnaire de paquets** : [uv](https://docs.astral.sh/uv/)

---

## 📁 Structure

```
.
├── notebooks/                  # 7 TPs + défi final
│   ├── tp1_regression.ipynb
│   ├── tp2_classification_binaire.ipynb
│   ├── tp3_multiclasses.ipynb
│   ├── tp4_cnn.ipynb
│   ├── tp5_regularisation.ipynb
│   ├── tp6_hyperparametres_compression.ipynb
│   ├── tp7_texte_nlp.ipynb
│   └── defi_moons_romain.ipynb  # Défi final (client Datalys)
├── models/                     # Modèles entraînés sauvegardés
│   ├── modele_final.keras
│   └── modele_final.tflite
├── pyproject.toml              # Dépendances et configuration
├── .python-version             # Version Python (3.13)
└── .gitignore
```

---

## 🎓 Format pédagogique

Chaque notebook suit une structure identique :

- **🎯 Étape** : cellule à compléter par l’étudiant (consigne + indice)
- **✅ Contrôle** : vérification automatique (ne pas modifier) avec helper `controle(condition, ok, ko)`
- **✍️ Question** : réponse écrite attendue

Les noms de variables sont imposés par les contrôles : les respecter est essentiel.

---

## ✍️ Auteurs

[TheRealRPI](https://github.com/TheRealRPI) - 🧙 Sorcier de la Data | Data Engineer en formation - Simplon.co

---

## 📜 Licence

Projet académique - usage éducatif
