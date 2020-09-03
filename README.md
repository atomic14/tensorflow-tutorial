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
