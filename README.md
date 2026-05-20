🎭 DeepFER — Facial Emotion Recognition with CNN
A real-time facial emotion recognition web application built using Streamlit and Convolutional Neural Networks (CNNs). This project detects faces and classifies emotions from images or live video streams.
---
📌 Project Title
Facial Emotion Recognition Using Convolutional Neural Networks (CNN)
---
📖 Introduction
Facial Emotion Recognition (FER) is a key area in computer vision and artificial intelligence. It enables machines to identify human emotions from facial expressions, with applications in:
Human-computer interaction
Healthcare
Surveillance systems
Marketing and user behavior analysis
This project develops a CNN-based model to accurately recognize human emotions from facial images.
---
🎯 Objectives
Build a CNN model to classify facial emotions
Evaluate performance using a standard FER dataset
Analyze accuracy and efficiency
Explore real-world applications of the system
---
📚 Literature Review
Traditional FER methods relied on handcrafted features such as:
Local Binary Patterns (LBP)
Histogram of Oriented Gradients (HOG)
Scale-Invariant Feature Transform (SIFT)
These approaches struggled with variations in lighting, pose, and occlusion.
Deep learning, especially CNNs, significantly improved FER by:
Automating feature extraction
Increasing accuracy and robustness
Popular datasets used in research:
FER2013
AffectNet
CK+
---
⚙️ Methodology
1. Dataset & Preprocessing
Dataset: FER2013 (35,887 labeled images)
Emotion Classes:
Angry
Disgust
Fear
Happy
Sad
Surprise
Neutral
Preprocessing steps:
Resize images to uniform dimensions
Normalize pixel values
Convert to grayscale
Apply data augmentation:
Rotation
Flipping
Zooming
---
2. CNN Model Architecture
Convolutional Layers: Extract features using ReLU activation
Pooling Layers: Max pooling for dimensionality reduction
Fully Connected Layers: Perform classification
Output Layer: Softmax activation for probability distribution
---
3. Training the Model
Loss Function: Categorical Crossentropy
Optimizer: Adam
Validation: Separate validation set to monitor performance
---
4. Evaluation Metrics
Accuracy
Confusion Matrix
ROC Curve
---
📊 Results and Discussion
Training and validation accuracy and loss are analyzed
Model performance is evaluated across all emotion classes
Challenges:
Class imbalance
Overfitting
Misclassification (e.g., Fear vs Surprise)
Comparative Analysis:
Compared with state-of-the-art FER models
---
✅ Conclusion
CNNs prove highly effective for facial emotion recognition. The model demonstrates strong performance, with scope for further optimization and enhancement.
---
🚀 Future Work
Implement advanced architectures (ResNet, Inception)
Deploy real-time emotion detection in video streams
Detect compound emotions and micro-expressions
Use transfer learning and ensemble models
---
📎 References
Goodfellow, I., et al. (2013) — Challenges in Representation Learning
LeCun, Y., et al. (1998) — Gradient-Based Learning Applied to Document Recognition
Mollahosseini, A., et al. (2017) — AffectNet Dataset
---
📂 Appendices
Appendix A: CNN architecture and hyperparameters
Appendix B: Sample implementation code
Appendix C: Additional evaluation figures and tables
---
💻 Tech Stack
Python
TensorFlow / Keras
OpenCV
Streamlit
---
