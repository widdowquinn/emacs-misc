# README.md - emacs
This repository contains files/other help for `emacs`. I don't expect anyone else will find it useful, but it's here if you want it.

### `init.el`

Emacs configuration file, to be placed at an appropriate location, e.g `./emacs.d/init.el`. This config file does a couple of useful things:

* Installs packages from a predefined list on startup (if not already present)
* Constructs a Python IDE within Emacs, from `elpy`, `pyenv`, `flake8`, `pep8`, and `flycheck`
* Enables `web-mode` for a range of files
* Sets the Emacs `$PATH` to be the same as that of the shell
* Allows use of the `Meta` key for printing `#` - a godsend on Mac laptops!
* Turns off the startup message
* Applies the `material` theme
* Turns on and formats line numbering

### `elpy-requirements.txt`

A requirements file for `pip` that can be used to ensure that the appropriate dependencies are available for `elpy` in the relevant Python installation.

```bash
pip install -r elpy-requirements.txt
```