# Comparison of Vision Transformer (ViT) and Pre-Trained Models for Image Classification

## Introduction
This project evaluates the performance of Vision Transformers (ViT) and pre-trained Convolutional Neural Networks (CNNs) on the CIFAR-10 dataset. The objective is to compare their generalization capabilities and effectiveness in image classification.

---

### **Generalization Capability**
- **Pre-trained ViT** achieved the highest test accuracy of **96.10%**, significantly outperforming the custom ViT (**62.17%**) and ResNet18 (**89.34%**).
- Highlights the effectiveness of pre-trained transformers, especially for shorter training durations.

### **Performance Comparison**
- **Pre-trained ViT** showed superior results across all metrics.
- **ResNet18** delivered strong performance (**89.34% accuracy**) but was outpaced by the pre-trained ViT.
- **Custom ViT's lower accuracy** underscores the critical role of pre-training in transformers.

### **Training Efficiency**
- Pre-trained models converged in just **3 epochs**, compared to the custom ViT's **20 epochs**.
- This demonstrates the efficiency and practicality of transfer learning.

### **Generalization vs Overfitting**
- **ResNet18** exhibited signs of overfitting with strong training performance but relatively lower test accuracy.
- The **pre-trained ViT** maintained high test accuracy, showcasing robustness on unseen data.

---

### Model Test Accuracy:
- **Custom ViT:** 62.17%  
- **Pre-trained ViT:** 96.10%  
- **ResNet18:** 89.34%  



