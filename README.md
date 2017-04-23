# Darkburn Theme

## This fork is no lorger maintained !!!

On February of 2016 a patch was merged into the original Zenburn theme that
makes this fork obsolete. See
commit
[b057fa5b2e0ad3a10d15709a3748156dd5282909](https://github.com/bbatsov/zenburn-emacs/commit/b057fa5b2e0ad3a10d15709a3748156dd5282909).

The original Zenburn theme now has an easy customization feature. To make the
changes from this theme on the original, use the following:

    (defvar zenburn-override-colors-alist
      '(("zenburn-bg" . "#111111")))
    (load-theme 'zenburn t)

----

A not-so-low contrast color theme for Emacs. A mod of the
[Zenburn](http://github.com/bbatsov/zenburn-emacs) theme for Emacs 24 by
Bozhidar Batsov to make backgrounds a little darker.

To install it, look for `darkburn-theme` in MELPA or click on the badge below.

[![MELPA](http://melpa.org/packages/darkburn-theme-badge.svg)](http://melpa.org/#/darkburn-theme)

## Screenshot

![Dark Burn Theme for Emacs 24](/Emacs24-DarkBurnTheme.png "Dark Burn Theme for Emacs 24")
