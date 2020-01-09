# PyData Heidelberg Workshop - 2020-01-09

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gist/jtpio/pydata-heidelberg-workshop/master)

## Setup

```bash
git clone https://github.com/jtpio/pydata-heidelberg-workshop
cd pydata-heidelberg-workshop/

conda env create
conda activate voila-starter-pack
chmod +x ./postBuild

# On Windows, you can run the `jupyter` commands from the postBuild file manually
./postBuild

jupyter lab workshop.ipynb
```

Alternatively, Voila can also be installed via `pip` or `conda`:

```bash
pip install voila
```


```bash
conda install voila -c conda-forge
```
