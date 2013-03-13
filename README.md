dotvim
======
1. use
    - cd ~
    - cp -r .vim vim.bak;cp .vimrc vim.bak
    - git clone git@github.com:jiahut/dotvim.git
    - ln -s dotvim/.vim .vim
    - ln -s dotvim/.vimrc .vimrc
2. install
    - cd ~/dotvim
    - git submodule add http://github.com/tpope/vim-fugitive.git .vim/bundle/fugitive
    - git submodule update --init
    - git submodule foreach git pull origin master
3. unzip
    - cd ~/dotvim/.vim/bundle/
    - unzip ~/download/snipMate.zip -d .
3. inspire by [Synchronizing plugins with git submodules and pathogen][]

[Synchronizing plugins with git submodules and pathogen]: http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen
