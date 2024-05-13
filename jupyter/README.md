# Jupyter

Create the Conda environment:

```bash
conda env create -n playground -f environment.yml
```

Activate the Conda environment:

```bash
conda activate playground
```

Open notebook:

```bash
jupyter notebook Notebook.ipynb 
````

Export the Conda environment:

```bash
conda env export > environment.yml
```

Deactivate the Conda environment:

```bash
conda deactivate
```

Delete the Conda environment:

```bash
conda env remove -n playground
```