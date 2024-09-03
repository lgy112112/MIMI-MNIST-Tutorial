![mimi](e152d203cd40d9efb1908e3b0a15be2.png)

<p align="center">
  <img src="https://img.shields.io/badge/Mimi%20Cat%20Knight-%E2%98%95%20Coffee%20Lover-orange" alt="Mimi Cat Knight" />
  <img src="https://img.shields.io/badge/NMIXX-See%20That%20-purple" alt="NMIXX" />
  <img src="https://img.shields.io/badge/NEWJEANS-Cool%20With%20You-blue" alt="NEWJEANS" />
  <img src="https://img.shields.io/badge/tripleS-1%20To%2024-blue" alt="tripleS" />
  <img src="https://img.shields.io/badge/KAN%20IN-Code%20Shit-green" alt="KAN IN" />
</p>


---

# 🎨 MNIST-Tutorial

Welcome to the **MNIST-Tutorial** repository! 🚀 This is your one-stop shop for playing around with the classic MNIST dataset in some creative ways. We've got everything from traditional CV methods to a multi-view approach. Dive in and enjoy! 😄

Here's the modified README with the new file `kan_train_seq.ipynb` and updated results table:

---

## 📂 Directory Overview

- **[`get_data.ipynb`](get_data.ipynb)** 🕵️‍♂️  
  Start here! This notebook is your data detective, exploring the MNIST dataset to uncover all its secrets. Perfect for getting to know your data better.

- **[`train.csv`](train.csv)** 📊  
  The heart of the project! This file contains the MNIST dataset stored as sequences. Each sequence has a length of 784, representing the flattened 28x28 grayscale images.

- **[`train.ipynb`](train.ipynb)** 🖼️  
  Feeling traditional? This notebook transforms the 784-length sequences back into 28x28 images and trains a model using classic computer vision techniques. Because sometimes, old school is the best school!

- **[`train_seq.ipynb`](train_seq.ipynb)** 📈  
  Why complicate things? This notebook skips the reshaping and trains directly on the original sequences. Simple, yet effective!

- **[`kan_train_seq.ipynb`](kan_train_seq.ipynb)** 🔄  
  A new perspective on the sequence approach! This notebook introduces a different way to train directly on the original sequences, trying to squeeze a bit more out of the simple approach.

- **[`train_multi_branch.ipynb`](train_multi_branch.ipynb)** 🔍🔬  
  Can't decide between image and sequence? Why not both?! This notebook uses a multi-view approach, combining the power of both perspectives to train a model. Two heads (or views) are better than one!

## 📊 Results Comparison

Here's how our different methods stack up on validation accuracy:

| Method                          | Validation Accuracy      |
|---------------------------------|--------------------------|
| `train.ipynb`                   | 0.9802380800247192       |
| `train_seq.ipynb`               | 0.9745237827301025       |
| `kan_train_seq.ipynb`           | 0.9672619104385376       |
| `train_multi_branch.ipynb`      | 0.9923809766769409       |

As you can see, the multi-view approach gives us the best results! 🏆 However, each method brings something valuable to the table.

## 🚀 Let's Get Started

Clone the repo, open up the notebooks, and start experimenting with the MNIST dataset in these different ways. Whether you're a fan of images, sequences, or both, there's something here for you! 💻🎉

