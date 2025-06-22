## 📌 Project Objectives

This project investigates the effectiveness of convolutional neural networks (CNNs) for the binary image classification task of distinguishing between cats and dogs. The core objectives are outlined as follows:

### 1. **Develop a Baseline CNN Model**
- Implement a simple CNN from scratch using TensorFlow/Keras.
- Establish a performance baseline in terms of training and validation accuracy and loss.

### 2. **Experiment with Architectural Modifications**
- Design several modified versions of the baseline model by altering the number of filters, layer configurations, and regularization techniques.
- Evaluate how these changes affect model complexity, overfitting, and classification performance.

### 3. **Apply Data Augmentation Techniques**
- Improve generalization by introducing random transformations (e.g., cropping, flipping, zooming).
- Compare models trained with and without augmentation to assess its impact.

### 4. **Incorporate Transfer Learning**
- Use a pretrained CNN (MobileNetV2) as a feature extractor.
- Fine-tune the model’s top layers for the binary classification task to measure the performance benefit of transfer learning.

### 5. **Conduct Comparative Evaluation**
- Train all models under equal conditions (same dataset, preprocessing, and number of epochs).
- Compare training/validation accuracy, loss curves, overfitting tendencies, and number of parameters.
- Visualize results using bar charts, loss curves, overfitting gap plots, and training vs. validation scatter diagrams.

### 6. **Draw Insights and Recommendations**
- Analyze which model architecture yields the best trade-off between performance and complexity.
- Provide a rationale for architectural choices that led to significant improvements.