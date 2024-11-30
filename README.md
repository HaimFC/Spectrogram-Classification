Spectrogram Classification

## 1. Assignment Overview
This assignment focuses on designing and training neural networks for spectrogram classification. You will explore two architectures: a Multi-Layer Perceptron (MLP) and a Convolutional Neural Network (CNN). Starter code is provided for data processing.

---

### 1.1 Data 

#### Part (a) – 
- Load training and test data.
- Split training data into training and validation sets.
- Normalize pixel intensities to be in the range `[-0.5, 0.5]`.

#### Part (b) – 
- Implement a function `generate_plots()` to display spectrograms for different classes.

#### Part (c) – 
- Discuss the importance of a balanced dataset to prevent model bias and improve generalization.

#### Part (d) – 
- Convert class labels into numerical values using a helper function `convert_class_to_number()`.

#### Part (e) – 
- Implement `create_onehot()` to convert index notation into one-hot encoding for classification.

---

### 1.2 Model Architecture

#### Part (a) – MLP 
- Design an MLP with two layers: input to hidden and hidden to output.
- Provide a diagram of the architecture.

#### Part (b) – CNN 
- Implement a CNN model with multiple convolutional layers, followed by max pooling, and fully connected layers.
- Provide a diagram of the architecture.

---

### 1.3 Training 

#### Part (a) – Training Function 
- Implement `train_model()` to train the models using Adam optimizer and cross-entropy loss.

#### Part (b) – Hyperparameter Tuning 
- Experiment with learning rates, batch sizes, and architecture-specific parameters for optimal performance.

#### Part (c) – Training Curves 
- Provide learning curves for the best-performing models.

---

### 1.4 Testing

#### Part (a) – Test Accuracy 
- Report the test accuracy for the best-performing model using validation results.

#### Part (b) – Predictions
- Display examples of correctly and incorrectly classified spectrograms.

#### Part (c) – Model Comparison
- Compare the capacity, layers, and performance of MLP and CNN models.
- Discuss advantages and disadvantages of each architecture.

---

## Notes
- Save checkpoints during training for reproducibility.
- Include training and validation curves in your submission.

## References
- [Data](https://drive.google.com/file/d/1VJ8xHKqd_aFrSwZRMyTpOnsIwnWqAfkh/view)
