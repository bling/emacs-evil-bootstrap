emacs-evil-bootstrap
====================

The quickest way to trying out Vim in Emacs

Install
=======

`git clone https://github.com/bling/emacs-evil-bootstrap.git ~/.emacs.d`

Settings
========

This bootstrap changes 3 settings that are enabled by default:

*  `evil-search-module` is set to the `evil-search` module instead of the default `isearch` module.
*  `evil-want-C-u-scroll` is set true.  The default binding is the Emacs function `universal-arguments`.
*  `evil-C-w-in-emacs-state` is set to true.  This gives you window bindings in all of Emacs (instead of the default which cuts a region).

License
=======

MIT License. Copyright (c) 2013 Bailey Ling.
