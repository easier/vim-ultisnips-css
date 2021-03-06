# CSS snippets for UltiSnips.vim
#### Style faster

My collection of CSS snippets lets you type CSS faster. Just use these on a
Vim+UltiSnips setup and you can type *abbreviations* of declarations to expand
to full CSS like so:

```
db<tab>
m0<tab>
fl<tab>
```

To become:

``` css
display: block;
margin: 0;
float: left;
```

See [this list][list] for a full list of snippets.

[list]: https://github.com/rstacruz/vim-ultisnips-css/blob/master/snips.yml

You'll need
-----------

 * [Vim](http://www.vim.org)
 * [UltiSnips](https://github.com/SirVer/ultisnips)
 * [Pathogen](https://github.com/tpope/vim-pathogen) or [Vundle](http://github.com/gmarik/vundle) (optional but recommended)

Installation via Vundle
-----------------------

Add to your .vimrc:

    Bundle 'SirVer/ultisnips'
    Bundle 'rstacruz/vim-ultisnips-css'

Installation via Pathogen
-------------------------

    $ git clone https://github.com/SirVer/ultisnips.git ~/.vim/bundle/ultisnips
    $ git clone https://github.com/rstacruz/vim-ultisnips-css.git ~/.vim/bundle/vim-ultisnips-css

Installation via Vim without Vundle/Pathogen
--------------------------------------------

It's possible but I won't even tell you how to. Do yourself a favor and start using Vundle or Pathogen.

Contributing
------------

Just edit the YML file, don't edit the snippet files themselves.

Acknowledgements
----------------

© 2012, Rico Sta. Cruz. Released under the [MIT License](http://www.opensource.org/licenses/mit-license.php).

 * [My website](http://ricostacruz.com) (ricostacruz.com)
 * [Github](http://github.com/rstacruz) (@rstacruz)
 * [Twitter](http://twitter.com/rstacruz) (@rstacruz)
