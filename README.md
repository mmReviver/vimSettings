vimSettings
===========

My own VIM settings and plugins, based on Jeffy-vim

Other Manager/Plugin required:

- Jeffy-vim

https://github.com/bighaidao/jeffy-vim

```bash
git clone https://github.com/bighaidao/jeffy-vim
cd jeffy-vim
# backup the original settings first
cp -r ~/.vim ~/.vim_backup
cp -r ~/.vimrc ~/.vimrc_backup
# inatall the plugins
./install.sh
```

- etslabs/python-vimrc

https://github.com/ets-labs/python-vimrc

```bash
sudo apt install build-essential cmake python3-dev
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ets-labs/python-vimrc/master/setup.sh)"
python3 ~/.vim/bundle/YouCompleteMe/install.py --clang-completer --go-completer --java-completer
```

- SpaceVim

https://spacevim.org

https://github.com/SpaceVim/SpaceVim

```bash
curl -sLf https://spacevim.org/install.sh | bash
```
