First, install the dependencies:

```bash
pip install -r requirements.txt
```

Install matplotlib widgets and generate static data:

```bash
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter lab build
```

And run jupyter with `jupyter-lab`.
