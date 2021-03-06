ruby-hash-syntax.el
===================

Adapted from the method used by TextMate, this library provides
a command `ruby-hash-syntax-toggle` which attempts to automatically
convert the selected region of ruby code between 1.8 and 1.9 hash styles.

Installation
=============

If you choose not to use one of the convenient packages in
[Melpa][melpa] and [Marmalade][marmalade], you'll need to add the
directory containing `ruby-hash-syntax.el` to your `load-path`, and then
`(require 'ruby-hash-syntax)`.

Usage
=====

Add the following to your emacs init file:

    (require 'ruby-hash-syntax)

Then select a block of ruby code containing a hash literal (perhaps
using `mark-sexp`), and run the `ruby-hash-syntax-toggle` command:

    M-x ruby-hash-syntax-toggle

You might like to bind that command to a key in `ruby-mode-map`.

[marmalade]: http://marmalade-repo.org
[melpa]: http://melpa.milkbox.net

<hr>

[![](http://api.coderwall.com/purcell/endorsecount.png)](http://coderwall.com/purcell)

[![](http://www.linkedin.com/img/webpromo/btn_liprofile_blue_80x15.png)](http://uk.linkedin.com/in/stevepurcell)

[Steve Purcell's blog](http://www.sanityinc.com/) // [@sanityinc on Twitter](https://twitter.com/sanityinc)
