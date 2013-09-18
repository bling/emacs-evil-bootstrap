emacs-evil-bootstrap
====================

The quickest way to trying out Vim in Emacs

Install
=======

`git clone https://github.com/bling/emacs-evil-bootstrap.git ~/.emacs.d`

Settings
========

This bootstrap changes 3 evil-mode settings from their default values:

*  `evil-search-module` is set to `evil-search` instead of the default `isearch` module.
*  `evil-want-C-u-scroll` binds `C-u` to scroll up instead of the default `universal-argument` function.
*  `evil-C-w-in-emacs-state` binds `C-w` to control windows just like Vim instead of the default of cutting a region.

License
=======

MIT License. Copyright (c) 2013 Bailey Ling.
