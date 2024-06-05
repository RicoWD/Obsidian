https://github.com/42School/norminette

Requires python3.8+ (3.8, 3.9, 3.10, 3.11)

### Directly inside your global commands

Install using pip.

```shell
python3 -m pip install --upgrade pip setuptools
python3 -m pip install norminette
```

Install using pipx.

```shell
sudo apt update
sudo apt install python3-setuptools
sudo apt install pipx
pipx install norminette
pipx ensurepath
```

Install using a virtual environment.

```shell
python3 -m venv $HOME/.venv
source $HOME/.venv/bin/activate
python3 -m pip install --upgrade pip setuptools
python3 -m pip install norminette
echo "export PATH=\$PATH:$HOME/.venv/bin" >> $HOME/.${SHELL##/bin/}rc
deactivate
```