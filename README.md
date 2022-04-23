# Meeting Agendas

[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)]( https://daanmatch.github.io/meeting-agendas/)

## Prerequisites

``` zsh
pip install -U jupyter-book
pip install ghp-import
pip install myst-parser
```

## Updating Jupyter Book

Rebuild HTML files:

``` zsh
jb build meetings
```

Push HTML content to GitHub pages branch

``` zsh
ghp-import -n -p -f _build/html
```
