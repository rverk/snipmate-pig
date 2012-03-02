`Snipmate snippets for PigLatin`

Installation
============
Use tpope's `pathogen.vim <https://github.com/tpope/vim-pathogen>`_ and install snipmate::

    cd ~/.vim/bundle
    git clone https://github.com/msanders/snipmate.vim

After that install the pig snippets::

    git clone http://github.com/rverk/snipmate-pig 

If you want to store repositories of plugins inside your own repository, use `git submodules <http://progit.org/book/ch6-6.html>`_::

    cd <repo root>
    git submodules init
    git submodule add http://github.com/rverk/snipmate-pig ~/.vim/bundle/snipmate-pig

update all your modules at once with::

    git submodules update

License
=======
GPL2+
