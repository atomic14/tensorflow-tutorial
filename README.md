# Tensorflow Tutorials

# Pre-requisites

Make sure you have python3 installed.

```
python --version
```

If this returns `Python 2.X.X` then try this:

```
python3 --version
```

This should return `Python 3.X.X`. If it fails then you will need to install Python3. Follow the instructions for your operating system to install it.

# Setup

We will be using a virtual environment for these tutorials. This keeps all the dependencies nicely isolated from the rest of your python installation.

This will create a virtual environment:

```
python3 -m venv venv
```

We then activate our virtual environment using:

```
. ./venv/bin/activate
```

It's also worth making sure `pip` is up to date:

```
pip install --upgrade pip
```

And then we install our dependencies using:

```
pip install -r requirements.txt
```

# Running

Activate the virtual environment that you created in the Setup steps:

```
. ./venv/bin/activate
```

And then run:

```
jupyter notebook .
```

You can now open the various notebooks.

# Notebooks

## 1. Binary Classification With TensorFlow

This notebook demonstrates how to classify inputs into 2 categories, True or False.

[![Video](https://img.youtube.com/vi/olkRurD-_t4/0.jpg)](https://www.youtube.com/watch?v=olkRurD-_t4)

## 2. Categorical Classification With TensorFlow

This notebook demonstrates how to classify inputs into multiple potential categories - e.g. Cat, Dog, Horse, Cow...

[![Video](https://img.youtube.com/vi/LPPTi38Zfqc/0.jpg)](https://www.youtube.com/watch?v=LPPTi38Zfqc)

## 3. Sparse Categorical Crossentropy Loss Function

This notebook demonstrates how to use the Sparse Categorical Crossentropy loss function which is similar to the Categorical Crossentropy cost function but removes the need for one-hot encoding the training labels.
