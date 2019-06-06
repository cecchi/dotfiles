# Powerline

## Installation

Install and configure `tmux` first. Then:

```sh
brew update
brew install coreutils
brew install python
pip install --upgrade pip setuptools
pip install psutil
pip install powerline-status

mkdir -p ~/.config/powerline/themes/tmux
cp cecchi.json ~/.config/powerline/themes/tmux/cecchi.json
```

Then, update `powerline/config_files/config.json`, setting `ext.tmux.theme` to `cecchi`. The installation directory of `powerline` is generally `/usr/local/lib/python2.7/site-packages/powerline`.

Finally, execute `tmux source-file ~/.tmux.conf` to reload the config.
