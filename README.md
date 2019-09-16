# JupyterLab + Binder

[![Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/binder-examples/jupyterlab/master?urlpath=lab/tree/index.ipynb)

JupyterLab is packaged with Binder repositories by default. In order to
run a JupyterLab session, you have two options:

## Start JupyterLab after you start your Binder

Do the following:

1. Launch a Binder instance (e.g., by clicking the Binder badge)
2. Replace `tree` at the end of your URL with `lab`.
3. That's it!

## Create a Binder link that points to JupyterLab

You can also create a Binder link that points to JupyterLab by adding the following
to the end of your link:

`?urlpath=lab`

You can point to a specific file using JupterLab by including a file path
beginning with `tree/` to the end of `urlpath`, like so:

`?urlpath=lab/tree/path/to/my/notebook.ipynb`

For example, the Binder badge above goes to the following URL:

`http://mybinder.org/v2/gh/binder-examples/jupyterlab/master?urlpath=lab/tree/index.ipynb`

Note: this repository also installs several JupyterLab extensions via a `postBuild` script, allowing
you to use JupyterLab's extensions and widgets functionality.

For a more complete demo of JupyterLab using Binder, see the
[JupyterLab Demo](https://github.com/jupyterlab/jupyterlab-demo). 
 
