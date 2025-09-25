**Date**: Sep 22, 2025

**Slides**: https://docs.google.com/presentation/d/1Fq5rMSVOiBy4PTwu4U1J-6fnbQo-ssCj3nnIOb1LbNI/edit?usp=sharing

* PyTorch: tensor, attributes, automatic differentiation
* FashionMNIST dataset
* [Dense](FashionMNIST_Dense.ipynb) NN architecture
* [Convolutional](FashionMNIST_SimpleCNN.ipynb) CNN architecture
* Git and GitHub

**Additional materials:**
* [What is torch.nn really?](https://docs.pytorch.org/tutorials/beginner/nn_tutorial.html)
* [The Matrix Calculus You Need For Deep Learning](https://explained.ai/matrix-calculus/index.html)

**Assignment 02** (due to Sep 29, 8:30 AM):

* Create [GitHub](https://github.com/) account.
* Play with FashionMNIST scripts (try to improve accuracy on the test set).
* Create your own image dataset and make it publicly available (2-5 categories, 100-300 images per category, cca 1000 images in total). Split it to train and test partitions (75% : 25%). See the required folder format below.
* Train a simple CNN on your dataset. It is ok if it is not optimal - we will improve it next week.
* Fill in the links to your GitHub and the dataset into the form (the link is on Slack).
* See [HW02_hints.ipynb](HW02_hints.ipynb) for hints.

### Dataset format

* **Top-level folder**: Name of your dataset (e.g., `animals_dataset`)

* **Next level**: Two subfolders — `train/` and `test/` — for training and testing data

* **Next level**: Each class of image (e.g., `cat/`, `dog/`) gets its own folder

* **Final level**: Actual `.jpg` files (image filenames don't matter)

```
animals_dataset/
├── train/
│   ├── cat/
│   │   ├── 001.jpg
│   │   ├── 002.jpg
│   │   └── ...
│   ├── dog/
│   │   ├── 003.jpg
│   │   ├── 004.jpg
│   │   └── ...
│   └── ... (more classes)
├── test/
│   ├── cat/
│   │   ├── 101.jpg
│   │   ├── 102.jpg
│   │   └── ...
│   ├── dog/
│   │   ├── 103.jpg
│   │   ├── 104.jpg
│   │   └── ...
│   └── ... (more classes)
```

