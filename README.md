#vim-espresso

[Espresso]:(https://github.com/mbadolato/iTerm2-Color-Schemes#espresso)
[Lightline]:(https://github.com/itchyny/lightline.vim)

This is a Vim colorscheme based on the [Espresso][] theme for iTerm2. It has
support for both GUI and terminal colors, and includes its own colorscheme for
[Lightline][].

##Installation

[Pathogen]: https://github.com/tpope/vim-pathogen
[Vundle]: https://github.com/gmarik/vundle

I definitely recommend using [Pathogen][] if you are not already:

    $ cd ~/.vim/bundle
    $ git clone https://github.com/gmoe/vim-espresso.git

Or alternatively use [Vundle][]: 

    Plugin 'gmoe/vim-espresso'
    :PluginInstall

Make sure to edit your `.vimrc` as well:

    set t_Co=256
    set background=dark
    colorscheme espresso
