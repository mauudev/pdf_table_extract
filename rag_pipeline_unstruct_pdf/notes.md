## packages estra para poner ready el jupyter notebook:

- pip install pexpect

solo si ya tenias el jupyter notebook instalado y no te funcionaba el kernel

- pip install ipykernel -U --force-reinstall

```bash
https://gist.github.com/iandanforth/f3ac42b0963bcbfdf56bb446e9f40a33
https://stackoverflow.com/questions/59690698/modulenotfounderror-no-module-named-lzma-when-building-python-using-pyenv-on
sudo apt-get install lzma
sudo apt-get install liblzma-dev
sudo apt-get install libbz2-dev
```

y despues volver a compilar python:

````
On Unix, Linux, BSD, macOS, and Cygwin::
```bash
    ./configure
    make
    make test
    sudo make install
````

error ejecutando jupyter notebook: "jupyter-notebook: command not found", solo instalas pip install "ipython[notebook]"
y vuelves a ejecutar el jupyter notebook
