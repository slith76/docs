## My Vim Cheat Cheet

- start Vim with Factory Settings: vim -u NONE -N

### Basics

- Configuration: ~/.vimrc && ~/.vim/ ...
- Mac: better Key-Strock-Speed:
  - Karabiner (https://pqrs.org/osx/karabiner/)
  - Seil (https://pqrs.org/osx/karabiner/seil.html.en)

### Tab Navigation

- gt - next Tab
- :tabedit file - open new with file

### Search

- :nohl - reset latest search highlight <C-n>

### Syntax Highlight

- :set syntax=markdown - set SH for Markdown

### Moving

- fs - jump to the next "s"
- vfs - jump to the next "s" and mark it
- $ - move to the end of a line
- 0 - move to the beginning of a line
- ^ - move to the first character of a line
- gg - jump to the first line of a file
- G - jump to the last line of a file
- <C>+u - move up a half page
- <C>+d - move down a half page
- H
- M
- L

- viw - mark inner word
- vaw - mark inner word + next character
- diw - delete inner word
- daw - delete inner word + next character

### Text Objects

- word: words without " ,.( ..." -> w
- WORD: words to next whitespace -> W
- paragraph -> p
- sentence -> s

gUis

- vit - select text in a tag
- cit - change inner text in a tag
- vat - select all with a tag
- cat - change the hole tag

### Tab Navigation

- gt - next tab
- ,n - next left tab
- ,m - next right tab

### Settings

- set number
- set number! - boolean inkrement
- set number? - query value
- set wrap
- setlocal - set only in current buffer

- set cursorline

- map - show all mapping

### Help

- :help
- <C-]> jump to the link
- <C-t> jump back
- :exit :q or ZZ

### Add and Sub

- <C>+a - add
- <C>+x - sub

### Autocompletion with jedi Plugin

- <C>-<Space> - autocomplete

### Folding

- set foldmethod=
- mark lines with <V> und fold with zf and unfold with za

### Changes/Jumps

- g; - jump to the last change position - back
- g, - jump to the last change position - forward
- :changes
- <C-O> - Jumplist back
- <C-I> - Jumplist forward
- :jumps

### Shell

- :shell - goto Shell, ctrl-d to exit
- :2,$!sort -t',' -k2 - sort lines from 2 to end by column 2
- Tipp: line selection with "V"



### Watchlist

- :set autowriteall - auto save
- Plugin: wookiehangover/jshint.vim

### Bookmarks

- :marks - list all bookmarks
- ma - set bookmark to "a"
- 'a - jump to bookmark "a"
- '' - jump to previous position
