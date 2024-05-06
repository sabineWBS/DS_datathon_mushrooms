# Virtual Environment (venv) Setup & Activation Guide

Setting up a virtual environment can help you manage dependencies for your Python project. Here's a step-by-step guide to set up and activate a virtual environment using the built-in venv module in Python.

## Prerequisites

- Python 3.3 or later (check with python --version or python3 --version)

## Step 1: Create a Virtual Environment

Navigate to your project directory (or wherever you want to create the virtual environment) and run one of the following commands:

### For Linux/Mac:

```bash
python3 -m venv myenv
```

### For Windows:

```bash
py -m venv myenv
```

This will create a directory called myenv (or whatever you named it) that contains the virtual environment (basically a bunch of directories and files).

## Step 2: Activate the Virtual Environment

### For Linux/Mac:

```bash
source myenv/bin/activate
```

### For Windows:

```bash
myenv\Scripts\activate
```

You should see (myenv) at the beginning of your command line prompt, indicating that you are in the virtual environment. Now you can install dependencies and run your project without worrying about dependency conflicts.

## Step 3: Deactivate the Virtual Environment

When you're done working in the virtual environment, you can deactivate it by running the following command:

```bash
deactivate
```
