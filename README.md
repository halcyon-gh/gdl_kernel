# GDL/IDL kernel for IPython/Jupyter

Demo [Notebook](demo.ipynb)

The current version was found to work with pexpect 4.6, jupyter 4.4, and jupyter-notebook 5.7. 

To install:
```
python setup.py install --prefix=~/.local
```
or
```
python3 setup.py install --prefix=~/.local
```

This should make an IDL directory containing the kernelspec in `~/.local/share/jupyter/kernels`, and place `idl_kernel.py` in `~/.local/lib/pythonX.X/site-packages`.

To run:
```
jupyter notebook 
#Select IDL kernel from dropdown menu
```
