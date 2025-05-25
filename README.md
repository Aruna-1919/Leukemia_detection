# 🧬 Leukemia Detection using HQC-Net

**Acute Lymphoblastic Leukemia (ALL)** is a severe form of blood cancer affecting both children and adults. Early and accurate detection is crucial for improving survival rates. This project presents **HQC-Net: Hybrid Quantum-Classical Network**, a novel approach that combines classical CNN-based feature extraction with Quantum Neural Networks (QNNs) for efficient and accurate leukemia classification.

---

## 🚀 Project Overview

Traditional methods of leukemia diagnosis rely on manual microscopic image analysis, which is time-consuming and error-prone. Deep learning approaches, particularly CNNs, have shown promise, but they are computationally expensive due to the large number of parameters in fully connected layers.

**HQC-Net** addresses this by:
- Using **Convolutional Neural Networks (CNNs)** (e.g., Simple CNN, ResNet50) to extract features from blood smear images.
- Passing these features to a **Quantum Neural Network (QNN)** for final classification.
- Reducing parameter count and improving efficiency using quantum principles like **superposition** and **entanglement**.

---

## 🗃️ Files in Repository

- `source_code.ipynb`: Main notebook with CNN + QNN implementation
- `index.html`, `result.html`: Web interface for deployment
- `README.md`: Project documentation
- `Batch_5_final.pptx`, `CSE_A_BATCH_5.pdf`, `base_1_prob.pdf`, `base_2_tech.pdf`: Supporting documents and reports

---

## 🔬 Methodology

- **Image Input Size**: 64×64 RGB blood smear images
- **CNN Models Used**: Simple CNN, ResNet50
- **Quantum Layer**: Implemented using PennyLane with 2 qubits
- **Hybrid Structure**:
  - CNN extracts features
  - Features passed to QNN using `AngleEmbedding` and `StronglyEntanglingLayers`
  - Measured via PauliZ and reshaped for final Dense layer classification

---

## 📊 Results

- ✅ **Accuracy**: 96.22%
- 📉 **Error Rate**: Very low misclassification observed
- ⚡ **Speed**: Image classification completed in under 1 second
- 🔍 **Robustness**: Tested against varied lighting and orientation conditions
- 📈 **Deployment-ready**: Easily portable for mobile/web-based applications

---

## 🗣️ Voice Interface

This project also integrates **Google Text-to-Speech (gTTS)** to vocalize the predicted medicine name, enhancing accessibility:

- 👓 Helps visually impaired users hear the classification result
- 🧓 Useful for elderly users with limited screen interaction
- 🚫 Assists non-literate users with spoken guidance
- 🎧 Enables hands-free operation in healthcare environments

---

## 📦 Dependencies

- TensorFlow / Keras
- PennyLane (for QNNs)
- NumPy, Matplotlib, Pandas
- gTTS (Google Text-to-Speech)
- Flask (for deployment interface)


