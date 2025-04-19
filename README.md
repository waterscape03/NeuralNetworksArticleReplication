# Overview
This repository contains the implementation of our replication study, aimed at verifying the methodology and results of the original paper on primate species classification using Convolutional Neural Networks (CNNs). As part of our academic research, we enhanced the model by addressing data handling issues, applying augmentation techniques, and improving model robustness.

# Replicated article
S. Kamepalli, V. K. K. Kolli, S. R. Bandaru, ”Animal Breed Classification and Prediction Using Convolutional Neural Network: Primates
as a Case Study,” VFSTR Fourth International Conference on Electrical, Computer and Communication Technologies (ICECCT), 2021. DOI:
10.1109/ICECCT52121.2021.9616928

# Link to dataset
https://www.kaggle.com/datasets/slothkong/10-monkey-species

# Objectives
- *Verify reproducibility* of the results reported in the original study.
- *Ensure proper dataset partitioning* (Train/Validation/Test) to prevent data leakage.
- *Enhance classification accuracy* through modifications such as dropout layers and dynamic learning rate scheduling.
- *Evaluate performance metrics* beyond accuracy, including precision, recall, F1-score, and confusion matrix analysis.

# Technologies used
- *Python* (Jupiter notebook)
- *PyTorch*
- *OpenCV* (Image preprocessing)
- *Matplotlib & Seaborn* (Visualization of results)
- *Scikit-learn* Evaluation metrics
- *Pandas & NumPy* Data processing and analysis
- *PIL (Pillow)* Image handling and manipulation
- *tqdm* Progress bar visualization for training iterations.

# Repository structure
NeuralNetworksArticleReplication/
├── /models
│   └── monkey_classifier71.pth 
├── README.md
└── nn_article_replication.ipynb
