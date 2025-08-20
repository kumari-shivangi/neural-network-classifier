# 🧠 Neural Network Classifier (From Scratch)

## 📌 Project Overview

This project is part of **Module 11: Neural Networks**.
The objective is to implement a simple **feedforward neural network from scratch** using only **NumPy**, without using external ML frameworks like TensorFlow or PyTorch.

The network is trained to recognize synthetic images of **letters A, B, and C**, represented as binary pixel patterns in a **5×6 grid (30 features)**.
Through this project, we understand the fundamentals of **weight initialization, forward pass, backpropagation, loss computation, and gradient descent optimization**.

---

## 📂 Dataset

* No external dataset is required.
* The images of **A, B, and C** are created manually as **binary arrays**.
* Each letter is flattened into a **1D vector of 30 values (0 or 1)**.

---

## 🛠️ Tech Stack

* **Python** (NumPy, Matplotlib)
* **Jupyter Notebook / Google Colab**

---

## ⚙️ Features Implemented

✔️ Defined binary image patterns for A, B, and C
✔️ Implemented a **two-layer feedforward neural network** (input → hidden → output)
✔️ Used **sigmoid activation** in hidden & output layers
✔️ Implemented **loss function (cross-entropy)**
✔️ Trained using **backpropagation + gradient descent**
✔️ Plotted **loss curve across epochs**
✔️ Tested model with unseen inputs

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/neural-network-classifier.git
   cd neural-network-classifier
   ```
2. Install required libraries:

   ```bash
   pip install numpy matplotlib
   ```
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook neural_network_from_scratch.ipynb
   ```

   or run in **Google Colab** by uploading the notebook.

---

## 📊 Results

* The neural network was able to correctly classify test inputs of letters **A, B, and C**.
* Training loss decreased gradually across epochs, showing **successful learning**.
* Demonstrated how even a simple NumPy-based model can **learn basic classification tasks**.

---

## 📝 Conclusion

This project gave hands-on experience with the **core building blocks of neural networks**:

* Representing images as vectors
* Forward pass computation
* Backpropagation and gradient updates
* Visualizing training performance

With this foundation, we are now prepared to explore **advanced deep learning** using frameworks like **TensorFlow** and **PyTorch**.

---

## 📌 Author

👩‍💻 Shivangi — Data Science Trainee, passionate about **Deep Learning & AI**

