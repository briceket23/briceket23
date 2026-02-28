# Cyrille Brice FOMAZOU TCHINDA
**Machine Learning Researcher | Medical Image Analysis | AI for Global Health**
📧 fomazoutchinda@gmail.com 
---
## 🎯 Professional Summary

Machine Learning Researcher specializing in medical image analysis and self-supervised learning for resource-limited healthcare settings. Experienced in developing computationally efficient, label-efficient AI diagnostic tools, with a strong focus on clinical interpretability and cross-dataset generalization.

## 🔬 Research Experience
**Lead Researcher** | *Laboratory of Methods, National Higher Polytechnic School of Douala, University of Douala, Cameroon* 
* Led the conceptualization, methodology development, and experimental design for AI-assisted malaria diagnosis systems.
* Developed a Domain-Aware Self-Supervised Learning (SSL) pipeline based on an enhanced SimCLR architecture with margin-augmented NT-Xent loss and hard negative mining.
* Achieved a 90% reduction in expert annotation requirements, maintaining a 96.3% diagnostic accuracy using only 10% of labeled training data.
* Engineered biologically-motivated image augmentation strategies (e.g., simulated focus variations, illumination correction) to preserve critical cellular morphology while expanding training datasets.
* Conducted systematic interpretability benchmarking across eight AI attribution methods, establishing Gradient SHAP as the optimal algorithm for clinical deployment.

## 💻 Technical Skills
* **Programming & Environment:** Python (3.8+), PyTorch (1.12+), CUDA (11.7+).
* **Machine Learning:** Self-Supervised Learning (SimCLR), Deep Learning Convolutional Networks (ResNet-18), Transfer Learning, Contrastive Learning.
* **Explainable AI (XAI):** Gradient SHAP, Integrated Gradients, Guided Backpropagation, LIME, Guided Grad-CAM.
* **Infrastructure & Optimization:** High-Performance Computing (HPC), NVIDIA GPUs, Automatic Mixed Precision (AMP), Distributed Training.
## 📄 Selected Research & Projects
**Domain-Aware Self-Supervised Learning for Cell-Level Malaria Classification** 
* *Role:* First Author & Lead Researcher.
* *Cross-Dataset Generalization:* Demonstrated superior zero-shot generalization on the external BBBC041 dataset (AUC = 0.777) by optimizing fine-tuning protocols.
* *Clinical Reliability:* Implemented temperature scaling to improve probability calibration, reducing expected calibration error to below 0.05 for trustworthy clinical uncertainty estimates.
* *Deployment Efficiency:* Verified that the complete inference pipeline operates efficiently on standard clinical computing infrastructure, achieving speeds of 100+ images per second on CPU-only systems.
