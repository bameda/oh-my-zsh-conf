oh-my-zsh-conf
==============

Configuration for my zsh shell and for oh-my-zsh


Packages needed
---------------

- zsh
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
- [zsh-nvm](https://github.com/lukechilds/zsh-nvm)
- ruby
- python-virtualenvwrapper


Setup
-----
1. Install all the packages needed.

2. Clone the repo to `~/.oh-my-zsh-conf` and create the symlink

    ```
    git clone https://github.com/bameda/oh-my-zsh-conf ~/.oh-my-zsh-conf
    mv ~/.zshrc ~/.zshrc.oh-my-zsh-conf.old
    ln -s ~/.oh-my-zsh-conf/zshrc ~/.zshrc
    ```
    
3. Run `zsh` and check the output
