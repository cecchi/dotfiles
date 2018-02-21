# Powerline

## Installation

```sh
brew update
brew install coreutils
brew install python
pip install --upgrade pip setuptools
pip install psutil
pip install powerline-status

cp cecchi.json powerline/config_files/themes/tmux/cecchi.json
```

Then, update `powerline/config_files/config.json`, setting `ext.tmux.theme` to `cecchi`.
