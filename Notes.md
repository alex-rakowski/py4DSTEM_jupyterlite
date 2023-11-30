# Embedding code in website:
[c.f.](https://jupyterlite.readthedocs.io/en/stable/quickstart/embed-repl.html)
General repl stuff as well


## Github page: 

> https://alex-rakowski.github.io/py4DSTEM_jupyterlite/

## Auto execute code on startup for REPLS
```bash
https://alex-rakowski.github.io/py4DSTEM_jupyterlite/repl/index.html?import piplite;import micropip;await piplite.install("py4DSTEM==0.14.8", deps=False); await piplite.install("pylops");await piplite.install("emdfile");await piplite.install("ncempy");await piplite.install("dask");await micropip.install("colorspacious");await micropip.install("hdf5plugin");await micropip.install("gdown");await micropip.install("scikit-image");await piplite.install("scikit-optimize");


https://alex-rakowski.github.io/py4DSTEM_jupyterlite/repl/index.html?import piplite;import micropip;await piplite.install("py4DSTEM==0.14.8", deps=False); await piplite.install("pylops");await piplite.install("emdfile");await piplite.install("ncempy");await piplite.install("dask");await micropip.install("colorspacious");await micropip.install("hdf5plugin");await micropip.install("gdown");await micropip.install("scikit-image");await piplite.install("scikit-optimize");print("", "ignore this line and run import py4DSTEM",  sep="\n");
```

```html 
<iframe
  src='https://alex-rakowski.github.io/py4DSTEM_jupyterlite/repl/index.html?import piplite;import micropip;await piplite.install("py4DSTEM==0.14.8", deps=False); await piplite.install("pylops");await piplite.install("emdfile");await piplite.install("ncempy");await piplite.install("dask");await micropip.install("colorspacious");await micropip.install("hdf5plugin");await micropip.install("gdown");await micropip.install("scikit-image");await piplite.install("scikit-optimize");'
  width="100%"
  height="100%"
></iframe>
```


```bash
#this is what works
https://alex-rakowski.github.io/py4DSTEM_jupyterlite/repl/index.html?theme=JupyterLab%20Dark&kernel=python&toolbar=1&code=print("",%20"ignore this line%20and%20run%20import%20py4DSTEM",%20sep="\n");import%20piplite;import%20micropip;%20await%20piplite.install(%22py4DSTEM==0.14.8%22,%20deps=False);%20await%20piplite.install(%22pylops%22);await%20piplite.install(%22emdfile%22);await%20piplite.install(%22ncempy%22);await%20piplite.install(%22dask%22);await%20micropip.install(%22colorspacious%22);await%20micropip.install(%22hdf5plugin%22);await%20micropip.install(%22gdown%22);await%20micropip.install(%22scikit-image%22);await%20piplite.install(%22scikit-optimize%22);await%20piplite.install(%22spgl1%22);
```

## Some good Docs 
Checking github deploment locally: 
> https://jupyterlite.readthedocs.io/en/stable/howto/deployment/github-pages.html

## Running index.html doesn't really help

## Some cool things about ipywidgets
> https://ipywidgets.readthedocs.io/en/latest/_static/lab/

## Good playground to play with 
> https://jupyterlite.github.io/demo/lab/index.html

# NEED TO SET UP SOME ENVRIONMENT PERMISSIONS 
> https://github.com/alex-rakowski/pylops/settings/environments/1758994739/edit

