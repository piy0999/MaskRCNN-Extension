# Step 1 - Create a Conda virtual environment

We will be using Anaconda with python 3.6. If you don't have Anaconda, follow this tutorial https://www.youtube.com/watch?v=T8wK5loXkXg

Create a anaconda virtual environment by:
`conda create -n MaskRCNN anaconda python=3.6`


# Step 2 - Install the Dependencies

Activate the virtual environment and install dependencies:

```
conda activate MaskRCNN
pip install -r requirements.txt
```

# Step 3 - Install pycocotools

- Note: pycocotools requires Visual C++ 2015 Build Tools. Download it from [here](https://www.visualstudio.com/downloads/#build-tools-for-visual-studio-2017) if needed.
- Install pycocotools
  `pip install git+https://github.com/philferriere/cocoapi.git#subdirectory=PythonAPI`

# Step 4 - Launch Jupyter

`jupyter notebook`