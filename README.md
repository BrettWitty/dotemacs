dotemacs
========

This is my Emacs setup, inspired by [Sacha Chua's .emacs](http://sachachua.com/blog/dotemacs).

I have a very minimal `.emacs` file, which loads some minimal requirements and then runs the `bew_config.org` file, which is a set of Emacs configurations written in a literate programming style. Org-babel turns the org file into an elisp file and runs it.

I try to maintain a very small custom.el (`bew_custom.el`) so I know where all the settings are in my `bew_config.org`.
