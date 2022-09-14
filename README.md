# python-lsp-autoimport
Auto Import plugin for [python-lsp-server](https://github.com/python-lsp/python-lsp-server).

This plugin will run [autoimport](https://lyz-code.github.io/autoimport/) and [isort](https://pycqa.github.io/isort/) on your code.

pylsp plugin code is taken from [pyls-isort](https://github.com/paradoxxxzero/pyls-isort).


# Installation

Install in same environment as python-lsp-server. I recommend to use pipx:

```bash
pip install --user pipx
pipx install python-lsp-server
pipx inject python-lsp-server python-lsp-autoimport 
```
