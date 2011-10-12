****************
 nose.vim
****************

A simple compiler for executing nosetests on VIM. Originally written by Olivier Le Thanh Duong at and modified by lambdalisue. Useful to use with vim-makegreen_

See http://blog.staz.be/?post/2010/09/04/Python-unit-test-and-vim for find how to use it with vim-makegreen_

nose-machineout
==============================
modified version use nose-machineout_ for convinience so you have to install it as well as nose_::

    sudo pip install nose
    sudo pip install git+git://github.com/nvie/nose-machineout.git#egg=nose_machineout

.. _nose-machineout: https://github.com/nvie/nose-machineout
.. _nose: http://readthedocs.org/docs/nose/en/latest/
.. _vim-makegreen: https://github.com/reinh/vim-makegreen

how to install
============================
use vundle_ or pathogen_ is recommended or simply extract to your vim directory

.. _vundle: https://github.com/gmarik/vundle
.. _pathogen: http://www.vim.org/scripts/script.php?script_id=2332

and write the following code to your ``ftplugin/python.vim``::

    set compiler=nose



