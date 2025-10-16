# Python101
The Mac will have a pre-installed system-provided version of Python. This is typically installed in `/usr/bin/python3'. 

```shell
which python3
/usr/bin/python3
```

To install a newer version as well as manage several versions it is recommended to use pyenv (a tool to manage Python similar to jenv for Java)

```shell
brew install pyenv
...

pyenv install 3.13.9
pyenv global 3.13.9
pyenv versions
  system
* 3.13.9
```

Note: you will need to configure pyenv for your shell
I use fish so from the fish shell run the init command
This will provide a set of instructions to follow including editing the `config.fish` file

```shell
pyenv init
```

You then get the latest version

```shell
python3 --version
Python 3.13.9
```

