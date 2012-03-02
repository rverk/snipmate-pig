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


Featured snippets
=================
**Registering** all your .jar files can be a pain, this will make it easier::

    regloc : `register local`. Searches for *.jar in ./ and registers them
    reglib : `register lib`. Searches for *.jar in /usr/lib/pig and registers them

**Joins** in PigLatin know several types, depending on inner or outer joins::

    ji : `join inner`. Select 1 through 4 for normal, skewed, replicated or merge inner join
    jo : `join outer`. Select 1 through 3 for normal, skewed, replicated oiter join

**Compression** options require you to set multiple mapred options::

    setsc : `set snappy compression`. Outputs all options for job output, map output, tmpfile compression

License
=======
GPL2+
