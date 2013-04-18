README
======

![alanctkc dev environment](https://raw.github.com/alanctkc/dotfiles/master/screenshot.png)

Mac OS X
--------

**Install Homebrew:** [http://mxcl.github.io/homebrew/](http://mxcl.github.io/homebrew/)

Add Homebrew local paths to `PATH` if necessary.

**Install brewed software:** `brew install python mercurial vim tmux git`

**Replace system Python framework:** [http://stackoverflow.com/a/12697440/359287](http://stackoverflow.com/a/12697440/359287)

**Clone configs:** `git clone git@github.com:alanctkc/dotfiles.git ~/.config/dotfiles`

**Update submodules:**

	git submodule init  
	git submodule update
	
**Symlink configs:** ie. `ln -s ~/.config/dotfiles/.vimrc ~/.vimrc`

**Install virtualenvwrapper:** [http://virtualenvwrapper.readthedocs.org/en/latest/install.html](http://virtualenvwrapper.readthedocs.org/en/latest/install.html)

**Install IPython:** `pip install ipython`

**Install iTerm 2:** [http://www.iterm2.com/#/section/home](http://www.iterm2.com/#/section/home)

Import development colors.

**Install patched Inconsolata:** [https://github.com/Lokaltog/powerline-fonts](https://github.com/Lokaltog/powerline-fonts)

**Install Powerline:** `pip install --user git+git://github.com/Lokaltog/powerline`