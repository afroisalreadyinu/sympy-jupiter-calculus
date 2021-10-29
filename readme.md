First, install the dependencies:

```
pip install -r requirements.txt
```

Install matplotlib widgets and generate static data:

```
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter lab build
```

And run jupyter with `jupyter-lab`.
