# Installation of Python kernels for Jupyter

Install ```ipykernel```:

```
pip install ipykernel
```

Run the install script for a conda environment ```ds1```:

```
python -m ipykernel install --user --name ds1 --display-name ds1
```

Here the ```--user``` flag refers to the local installation. The meanings of other flags can be found from ```python -m ipykernel install -h```.


