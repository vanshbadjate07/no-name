# Deep Learning Practice Sets

5 practice sets for TensorFlow/Keras - each set has 2 coding questions.

## Run in Colab

| Set | Topic | Colab Link |
|-----|-------|-------------|
| Set 1 | Neural Network Basics & Cross-Entropy | [Open](https://colab.research.google.com/drive/1OMXUkS6IG8fCIknnvnP_d-xyN5qnUtbx?usp=sharing) |
| Set 2 | Dropout vs L2 Regularization | [Open](https://colab.research.google.com/drive/1roYRPqhngQIvrvXHg8aj32Cd-taCxrq3?usp=sharing) |
| Set 3 | Sequential vs Functional API | [Open](https://colab.research.google.com/drive/1BrmBGlDRF11_AopxHuXR972RY_-Jt-aQ?usp=sharing) |
| Set 4 | CNN for CIFAR-10 | [Open](https://colab.research.google.com/drive/1HgghcfgO2L2hf3WPDdqL9TSeBaw0hJB8?usp=sharing) |
| Set 5 | LSTM for IMDB Sentiment | [Open](https://colab.research.google.com/drive/1gGwOcQLDjbWjOozDq0utXLGNlU0nsFmQ?usp=sharing) |

## How to Run

1. Click any link above
2. Runtime → Run all (or Ctrl+F9)

## Quick Theory

### Set 1
- **Softmax** + **categorical_crossentropy** = multi-class classification
- Loss = -log(correct class probability)

### Set 2
- **Dropout(0.4)** = randomly disables 40% neurons
- **L2(0.001)** = adds penalty: loss + λ × Σ(weights²)

### Set 3
- **Sequential** = linear layer stack
- **Functional** = flexible, supports branching

### Set 4
- **Conv2D** = extracts features
- **MaxPooling** = reduces size
- **Flatten** = 2D to 1D for Dense layer

### Set 5
- **Embedding** = word to vector
- **LSTM** = remembers sequence context
- **pad_sequences()** = makes all sequences same length

## Loss Functions Reference

| Loss | When to Use |
|------|--------------|
| `binary_crossentropy` | 2 classes, sigmoid output |
| `categorical_crossentropy` | Multiple classes, one-hot labels |
| `sparse_categorical_crossentropy` | Multiple classes, integer labels |

## Activation Functions Reference

| Activation | Use Case |
|------------|----------|
| ReLU | Hidden layers |
| Softmax | Multi-class output |
| Sigmoid | Binary output |
