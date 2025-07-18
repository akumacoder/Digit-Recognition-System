
## Handwritten Digit Recognition System

This project implements a comprehensive **Convolutional Neural Network (CNN)** system for recognizing handwritten digits using the MNIST dataset. The system achieves over 95% accuracy through a deep learning architecture featuring three convolutional layers with MaxPooling, followed by fully connected layers with dropout regularization for overfitting prevention.

**Key Features:**
- **Intelligent Model Management**: Automatically loads pre-trained models or trains new ones with proper metric compilation
- **Advanced CNN Architecture**: Uses 32, 64, and 64 filter convolutions with ReLU activation and softmax output classification
- **Comprehensive Evaluation**: Includes confusion matrix analysis, classification reports, and confidence distribution studies
- **Interactive Visualizations**: Training history plots, sample prediction displays, and advanced confidence analysis with line graphs
- **Custom Digit Testing**: Creates and tests custom digit patterns programmatically

**Technical Implementation:**
Built using TensorFlow/Keras, NumPy, Matplotlib, and Scikit-learn, the system preprocesses 28×28 pixel grayscale images, applies categorical crossentropy loss with Adam optimization, and provides detailed performance metrics. The enhanced version includes sophisticated confidence analysis through multiple line graph visualizations, helping users understand model behavior patterns and prediction reliability across different digit classes.

**Applications**: Educational tool for understanding deep learning, prototype for OCR systems, and foundation for more complex computer vision projects.
