# deep_learning_gfu
Please create a conda environment, where the requirements are installed.
This can be achieved by:\

```
conda create -n ml pip
```
Afterwards, activate the environment:

```
conda activate ml
```

And install the requirements:

```
pip install -r requirements.txt
```

And finally, install the environment as a kernel available for Jupyter notebooks:

```
python -m ipykernel install --user --name=ml
```
