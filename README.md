🧠 Handwritten Digit Classification Using Neural Networks
📌 Author

K Chaitra Latha
MCA – Chanakya University

📖 Project Overview

This project focuses on Handwritten Digit Classification using Neural Networks on the MNIST dataset.

The objective is to analyze how increasing model complexity and applying optimization techniques like Backpropagation and Adam Optimizer improve classification accuracy.

📊 Dataset

Dataset: MNIST

60,000 training images

10,000 testing images

Image size: 28×28 pixels

Preprocessing:

Normalization (pixel values scaled to 0–1)

Flattening (28×28 → 784 input features)

Train-test split

🏗️ Model Architectures Implemented
🔹 1️⃣ Single-Layer Perceptron (SLP)

Dense layer with Sigmoid activation

Test Accuracy: ~92.5%

🔹 2️⃣ Multi-Layer Perceptron (MLP)

Hidden layer with ReLU activation

Output layer with Sigmoid

Test Accuracy: ~97.1%

🔹 3️⃣ Flatten + Two Dense Layers (Optimized Model)

ReLU activation

Adam Optimizer

Backpropagation

Test Accuracy: 97.79%

Training Accuracy: 99.17%

Lowest loss among all models

⚙️ Technologies Used

Python

TensorFlow

Keras

NumPy

Matplotlib

Jupyter Notebook

🔬 Training Details

Optimizer: Adam

Loss Function: Sparse Categorical Crossentropy

Epochs: 5–10

Batch Size: 32

Learning Mechanism: Backpropagation

📈 Performance Comparison
Model	Training Accuracy	Test Accuracy	Test Loss
SLP	92.62%	92.57%	0.267
2 Dense Layers	98.12%	97.16%	0.0966
Flatten + Dense	99.17%	97.79%	0.0813
💡 Key Insights

Hidden layers significantly improve feature extraction.

ReLU activation enhances learning efficiency.

Adam optimizer speeds up convergence.

Backpropagation enables effective weight updates.

Model complexity directly impacts accuracy and loss reduction.

🔐 Ethical Considerations

Responsible AI deployment

Awareness of dataset bias

Fairness and transparency in AI systems

📂 Repository Contents

Jupyter Notebook (Implementation)

Research Paper (.docx)

Presentation (.pptx)

README.md

🎯 Conclusion

The project demonstrates that deeper neural network architectures significantly improve handwritten digit classification performance. Proper preprocessing, activation functions, optimization techniques, and backpropagation play a critical role in achieving high accuracy.
