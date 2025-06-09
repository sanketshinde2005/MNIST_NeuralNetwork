# MNIST Digit Recognizer - Pure Numpy Neural Network

This project implements a neural network from scratch in **pure Numpy** to classify handwritten digits (MNIST dataset).

✅ No PyTorch / No TensorFlow / No Keras  
✅ Manual forward pass, backpropagation, gradient descent  
✅ Achieves **~90%+ accuracy**  
✅ Visualizes model predictions  

---

## Project Highlights

- Implemented **ReLU**, **softmax**, **one-hot encoding**
- **Two-layer fully connected neural network**:
  - 784 → 100 → 10 architecture
- Learned weights using **manual gradient descent**
- **Accuracy vs Iterations** plotted
- Displayed model predictions on test images

---

## Results

Achieved ~90% accuracy on training data. 

Example predictions:

| Digit Image | True Label | Model Prediction |
|-------------|------------|------------------|
| (0 image)   | 0          | 0                |
| (1 image)   | 1          | 1                |
| (6 image)   | 6          | 6                |

---
![WhatsApp Image 2025-06-09 at 17 12 37_f6904e96](https://github.com/user-attachments/assets/706a4730-d67e-4e07-a3fb-267439efbfda)


## How to Run

1. Clone this repo:
```bash
git clone https://github.com/yourusername/mnist-digit-recognizer-numpy.git
