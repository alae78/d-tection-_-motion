# **Détection des émotions à partir de textes**

## **Description du projet**
Ce projet consiste à développer un système de détection des émotions exprimées dans des textes, aussi bien en français qu’en anglais, en utilisant **DistilBERT**, une version allégée et optimisée de BERT. L’objectif principal est de prédire des émotions comme la joie, la tristesse, la colère ou la peur, indépendamment de la langue utilisée.

Grâce à l’adaptation et à l’entraînement de **DistilBERT** sur des données multilingues, ce projet fournit une solution performante et utile pour analyser les émotions dans des contextes nécessitant une prise en charge de plusieurs langues.

---

## **Fonctionnalités principales**
- Prédiction des émotions dans les textes en **français** et en **anglais**.
- Identification des émotions suivantes :
  - **Joie**, **Tristesse**, **Colère**, **Peur**, **Surprise**, et **Amour**.
- Utilisation de **DistilBERT** pour une analyse rapide et précise.
- Adapté aux environnements multilingues.

---

## **Installation**

### **Prérequis**
- Python 3.11
- Bibliothèques nécessaires :
  - `transformers`
  - `torch`
  - `pandas`
  - `streamlit` (si une interface est fournie)

### **Étapes**
1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/alae78/emotion_detection.git
   cd emotion_detection
