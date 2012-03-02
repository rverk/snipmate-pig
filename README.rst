`Snipmate snippets for PigLatin`

Installation
============
Use tpope's [pathogen.vim](https://github.com/tpope/vim-pathogen) and install snipmate::

    cd ~/.vim/bundle
    git clone https://github.com/msanders/snipmate.vim

After that install the pig snippets::

    git clone http://github.com/rverk/snipmate-pig 


If you are like me and your config in a repository and your plugins are also repositories use git submodules::

    cd <repo root>
    git submodules init (only if you don't have submodules yet)
    git submodule add http://github.com/rverk/snipmate-pig ~/.vim/bundle

update all your modules at once with::

    git submodules update

License
=======
GPL2+
