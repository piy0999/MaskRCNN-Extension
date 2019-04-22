# Step 1 - Create a Conda virtual environment

We will be using Anaconda with python 3.6. If you don't have Anaconda, follow this tutorial https://www.youtube.com/watch?v=T8wK5loXkXg

Create a anaconda virtual environment by:
`conda create -n MaskRCNN anaconda python=3.6`

# Step 2 - Install the Dependencies

Activate the virtual environment, install dependencies and run setup:

```
conda activate MaskRCNN
pip3 install -r requirements.txt
python3 setup.py install
```

# Step 3 - Install pycocotools

`pip3 install git+https://github.com/waleedka/coco.git#subdirectory=PythonAPI`

# Step 4 - Launch Jupyter

`jupyter notebook`

# Step 5 - Open MaskRCNN Notebook

Everything is in `MaskRCNN.ipynb`.

Note: Video processing is in `Video_Masker.ipynb`.
