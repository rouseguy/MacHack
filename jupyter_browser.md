# Changing default browser for Jupyter Notebook

Step 1:

```jupyter notebook --generate-config```

Step 2:

```mvim ~/.jupyter/jupyter_notebook_config.py```

In the file - change the following:

from
` # c.NotebookApp.browser = ''`

to 

`c.NotebookApp.browser = u'open -a /Applications/Google\ Chrome.app %s'`
