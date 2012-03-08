`Snipmate snippets for PigLatin`

Requirements
============
* Vim 7+
* `Pathogen <https://github.com/tpope/vim-pathogen>`_
* `Snipmate <https://github.com/garbas/vim-snipmate>`_ 

Installation
============
Just install like any other plugin::

    cd ~/.vim/bundle
    git clone http://github.com/rverk/snipmate-pig 

Add this to your ~/.vimrc to have vim recognize .pig files::

    augroup filetypedetect
        au BufNewFile,BufRead *.pig set filetype=pig syntax=pig
    augroup END 

For a small writeup and screenshots: `<http://www.ctrl-r.org/?p=161>`_

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
