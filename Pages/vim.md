
- vimfiles/pack/plugins/start下にプラグインをいれる

- ctrlp.vim

_vimrc
```vim
language messages English_United States
set langmenu=en_US.UTF-8

set nocompatible

set backspace=indent,eol,start

set nobackup
set expandtab
set nowrap

set number!
set showmode
set incsearch
set ignorecase
set smartcase
set showmatch
set hlsearch
set cursorline
"set cursorcolumn

set ruler
set showcmd
set wildmenu

set display=truncate

set fileencoding=utf-8
set fileformat=unix
set fileformats=unix,dos

syntax enable
filetype plugin indent on

"set background=light

colorscheme sorbet

"set guifont=Courier_New:h10:cANSI:qDRAFT
set guifont=Consolas:h10:cANSI:qDRAFT

packadd! editorconfig

nnoremap <LeftMouse> <LeftMouse>i
nmap <C-LeftMouse> <C-]>
imap <C-LeftMouse> <C-[><C-]>
map <X1Mouse> <C-O>
map <X2Mouse> <C-I>

let g:netrw_liststyle = 3

let g:ctrlp_user_command = ['.git', 'cd %s && git ls-files']
let g:ctrlp_map = '<c-k>'
let g:ctrlp_prompt_mappings = {
                        \ 'PrtSelectMove("j")': ['<c-n>', '<down>'],
                        \ 'PrtSelectMove("k")': ['<c-p>', '<up>'],
                        \ 'PrtHistory(-1)':    ['<c-j>'],
                        \ 'PrtHistory(1)':     ['<c-k>'],
                        \ }

set pythonthreehome=~\\AppData\\Local\\Programs\\Python\\Python312
set pythonthreedll=~\\AppData\\Local\\Programs\\Python\\Python312\\python312.dll

let g:jedi#goto_command = "<C-]>"
```
