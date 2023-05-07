<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vim/vim-original.svg" height="140" width="152" alt="vim logo"  />
</div>
<h2 align="left">gabrielroot's vim</h2>

### I've used [vim-bootstrap](https://github.com/editor-bootstrap/vim-bootstrap) to start my config set.
If you decide to clone this project, recommend to put it inside a preferred path, then create symbolic link for that, like:

```
ln -s /preferred_path/vim/.vim ~/.vim
ln -s /preferred_path/vim/.vimrc ~/.vimrc
```
So you can keep all settings isolated and "commitable"

```
/my_preferred_path:
  |── .git
  ├── assets
  │   ├── bgDark.jpg
  │   └── screenShot.png
  ├── .gitignore
  ├── LICENSE
  ├── README.md
  ├── .vim
  |   |── plugged
  │   ├── autoload
  │   │   └── plug.vim
  │   └── session
  └── .vimrc
  
/my_home_path:
  ├── .vim -> /my_preferred_path/vim/.vim
  └── .vimrc -> /my_preferred_path/vim/.vimrc
```

## OR

Just install by the common way:
> Overriding or merging existent config
- Move .vim/autoload/plug.vim to your $HOME path OR follow the instructins from the official repo to install the latest version: [vim-plug](https://github.com/junegunn/vim-plug)
- Move .vimrc to your $HOME path

###

<div align="center">
  <img height="500" src="https://raw.githubusercontent.com/gabrielroot/vim/main/assets/screenShot.png"  />
</div>

###
