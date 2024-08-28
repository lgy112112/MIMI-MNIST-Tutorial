![mimi](e152d203cd40d9efb1908e3b0a15be2.png)
---

# 🎨 MNIST-Tutorial

Welcome to the **MNIST-Tutorial** repository! 🚀 This is your one-stop shop for playing around with the classic MNIST dataset in some creative ways. We've got everything from traditional CV methods to a multi-view approach. Dive in and enjoy! 😄

## 📂 Directory Overview

- **[`get_data.ipynb`](get_data.ipynb)** 🕵️‍♂️  
  Start here! This notebook is your data detective, exploring the MNIST dataset to uncover all its secrets. Perfect for getting to know your data better.

- **[`train.csv`](train.csv)** 📊  
  The heart of the project! This file contains the MNIST dataset stored as sequences. Each sequence has a length of 784, representing the flattened 28x28 grayscale images.

- **[`train.ipynb`](train.ipynb)** 🖼️  
  Feeling traditional? This notebook transforms the 784-length sequences back into 28x28 images and trains a model using classic computer vision techniques. Because sometimes, old school is the best school!

- **[`train_seq.ipynb`](train_seq.ipynb)** 📈  
  Why complicate things? This notebook skips the reshaping and trains directly on the original sequences. Simple, yet effective!

- **[`train_multi_branch.ipynb`](train_multi_branch.ipynb)** 🔍🔬  
  Can't decide between image and sequence? Why not both?! This notebook uses a multi-view approach, combining the power of both perspectives to train a model. Two heads (or views) are better than one!

## 📊 Results Comparison

Here's how our different methods stack up on validation accuracy:

| Method              | Validation Accuracy      |
|---------------------|--------------------------|
| `train.ipynb`       | 0.9802380800247192        |
| `train_seq.ipynb`   | 0.9745237827301025        |
| `train_multi_branch.ipynb` | 0.9923809766769409  |

As you can see, the multi-view approach gives us the best results! 🏆

## 🚀 Let's Get Started

Clone the repo, open up the notebooks, and start experimenting with the MNIST dataset in these different ways. Whether you're a fan of images, sequences, or both, there's something here for you! 💻🎉
