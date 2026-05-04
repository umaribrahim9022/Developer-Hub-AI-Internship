# Task 3: Image Classification (CIFAR-10 or MNIST)

### 🎯 Objective
To build a Convolutional Neural Network (CNN) that can identify objects or digits from images.

### 🖼 Dataset
- **CIFAR-10:** Contains 60,000 32x32 color images in 10 classes (Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck).

### 🛠 Technical Implementation
- **Architecture:** 
  - **Convolutional Layers:** To extract spatial features from images.
  - **Pooling Layers:** To reduce dimensionality and computational load.
  - **Fully Connected (Dense) Layers:** For the final classification.
- **Framework:** TensorFlow/Keras or PyTorch.
- **Optimization:** Used 'Adam' optimizer and 'Sparse Categorical Crossentropy' loss.

### 📊 Key Insights
- CNNs perform significantly better on image data compared to standard Deep Neural Networks (DNNs) because they preserve spatial hierarchy.
- **Accuracy:** Achieved **X% Accuracy** on the test set.