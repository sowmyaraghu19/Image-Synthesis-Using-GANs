# 🧠 Image Generation with DCGAN on Custom Dataset

This project demonstrates how to build and train a Deep Convolutional Generative Adversarial Network (DCGAN) using PyTorch to generate realistic images from a custom image dataset. The model learns from the dataset and produces 64x64 synthetic images.

---

## 📌 Project Overview

* **Goal**: Generate new, realistic images using a GAN trained on your own dataset.
* **Approach**: Use a DCGAN architecture (a deep learning model combining convolutional layers and adversarial training).
* **Platform**: Implemented in a single Google Colab notebook.

---

## 🧰 Technologies Used

* *PyTorch*
* *Torchvision*
* *Google Colab*
* *Python*
* *COCO Subset Dataset (custom images)*

---

## 📁 Project Files

```
├── coco_subset_resized/        # Folder containing training images (JPG/PNG)
├── GAN_Image_Generation.ipynb  # Main Colab notebook with all code
├── README.md                   # Project documentation
```

---

## 🚀 Getting Started

1. Clone this repository
2. Ensure your dataset folder (`coco_subset_resized/`) is uploaded to the runtime.
3. Run the notebook cells sequentially to:

   * Load and preprocess the images
   * Define the Generator and Discriminator networks
   * Train the GAN using mixed precision
   * Generate and visualize sample images

---

## 📊 Results

* **Image Resolution**: 64x64 RGB
* **Training Speed**: Optimized with AMP (Automatic Mixed Precision) for faster execution
* **Loss Tracking**: Discriminator and Generator losses are printed each epoch for monitoring training progress

---

## 🖼️ Sample Output

After training, the model can generate new image samples similar to the training distribution. Generated images are displayed during training to visualize learning.

---

## 🤝 Contribution

Pull requests are welcome. If you find issues or want to enhance the model, feel free to contribute.
