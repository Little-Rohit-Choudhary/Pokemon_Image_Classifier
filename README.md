

# 🟡⚡ Pokémon Classifier 🔥🐉

This project is an image classification model that identifies **1,000 Pokémon species** using the **Pokémon Dataset 1000** from Kaggle.
A **DenseNet-201** model (transfer learning) was used for training, achieving **90%+ accuracy** on the validation set.

---

## 📁 Dataset 🧩

* **Source:** [https://www.kaggle.com/datasets/noodulz/pokemon-dataset-1000](https://www.kaggle.com/datasets/noodulz/pokemon-dataset-1000)
* **Images:** 26,000+
* **Classes:** 1,000 Pokémon categories
* The `.ipynb` file handles loading, preprocessing, training, and evaluation.

---

## 🤖 Model Architecture ⚙️

* **Base Model:** DenseNet-201 (ImageNet pretrained)
* **Classifier Head:** Global pooling → Dense → Softmax
* **Loss:** Categorical Crossentropy
* **Optimizer:** Adam
* **Image Size:** 224×224

---

## 🎯 Results ⭐

* **Accuracy Achieved:** **90%+**
* DenseNet-201 provides strong feature extraction for high-variation Pokémon images.

---

## 🚀 How to Run 🧪

1. Download the dataset from Kaggle.
2. Set correct dataset paths in the notebook.
3. Run all cells in the `.ipynb` file (Jupyter/Colab).

---

## 📄 Files Included

* `pokemon_classifier.ipynb` — Training + Evaluation + Prediction pipeline.

---

If you want, I can also make:
✨ a **super-short README**
🎨 a **fancy GitHub-styled README**
📊 a version with **images/sample outputs**
