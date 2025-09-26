# Impact of Data Duplication on Deep Neural Network-Based Image Classifiers: Robust vs. Standard Models  

This repository contains the implementation and experimental setup for the paper:  

**A. Aghabagherloo, A. Abadi, S. Sarkar, V. A. Dasu, and B. Preneel,  
"Impact of Data Duplication on Deep Neural Network-Based Image Classifiers: Robust vs. Standard Models,"  
Proc. IEEE Security and Privacy Workshops (SPW), May 2025, pp. 177–183.**  

---

## 📌 Overview  

This work investigates the **impact of data duplication** on the training and robustness of Deep Neural Networks (DNNs).  

- We begin with a **theoretical overview** of how duplications in the training set affect **standard** and **robust (adversarially trained)** models.  
- Next, we examine the effect of duplication when data points are **sampled from a Gaussian distribution**.  
- Finally, we explore the impact of duplication on the **CIFAR-10 dataset**, comparing both **standard models** and **adversarially trained models** under duplicated data conditions.  

Our findings reveal how duplication can alter generalization, robustness, and the decision boundaries of neural networks.  

---

## 📂 Repository Structure  

├── Code/
│ └── Implementation of experiments:
│ - Effect of duplication when data points are selected from a Gaussian distribution
│ - Experiments on CIFAR-10 with duplication added to both standard and adversarially trained models
│
├── paper_output_for_gaussian_distriibution/
│ └── Visualization of how duplications from Gaussian distribution affect decision boundaries
│
└── README.md


## 📊 Datasets  

- **Gaussian Distribution (synthetic data)**  
  - Used to study theoretical behavior of duplication and visualize decision boundary changes.  

- **CIFAR-10**  
  - 60,000 color images (32×32) in 10 classes.  
  - 50,000 training + 10,000 test images.  
  - Used to evaluate the practical effect of duplication on **standard** and **adversarially trained** models.  

---

📑 Citation
If you use this repository, please cite:

@inproceedings{Aghabagherloo2025Duplication,
  author={Aghabagherloo, A. and Abadi, A. and Sarkar, S. and Dasu, V. A. and Preneel, B.},
  booktitle={Proc. IEEE Security and Privacy Workshops (SPW)}, 
  title={Impact of Data Duplication on Deep Neural Network-Based Image Classifiers: Robust vs. Standard Models}, 
  year={2025},
  pages={177-183}
}
🙌 Acknowledgements
CIFAR-10 dataset by Alex Krizhevsky

Robust/adversarial training baselines from prior robustness research

