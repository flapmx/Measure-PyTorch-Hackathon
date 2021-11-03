# Overview

This repo contains some code-snippets from our integration. Namely, the PyTorch model instantiation and ONNX converter function.

## Quick start

1.) Install the dependencies using pip. We recommend doing this in a [virtual environment](https://docs.python.org/3/tutorial/venv.html#creating-virtual-environments).

```
pip3 install -r requirements.txt
```

2.) Run the script with python.

```
python3 snippet.py
```

You will see an ONNX file outputted to the root directory.

## Configuration

This snippet is easy to modify. 

Navigate to `snippet.py` and find the following section at the top of the file:

```
# Configurable options
MODEL_FILE = "model.py"
STATE_FILE = "squeezenet1_1-b8a52dc0.pth"
OUTPUT_PATH = "output.onnx"
```

These variables can be modified to take in any files PyTorch files of your choosing and output the appropriate onnx name. 