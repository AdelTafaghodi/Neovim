# Neovim
my neovim configuration

``` vim
:set number
:set mouse=a
:set title
:set clipboard=unnamedplus
:set cursorline
:set splitbelow splitright
:set wildmenu


call plug#begin()
 
Plug 'https://github.com/preservim/nerdtree' " NerdTree
Plug 'https://github.com/vim-airline/vim-airline' " Status bar
Plug 'https://github.com/ryanoasis/vim-devicons' " Developer Icons
Plug 'https://github.com/preservim/tagbar' " Tagbar for code navigation
Plug 'sheerun/vim-polyglot' "syntax highlighting for several programming languages.
Plug 'jiangmiao/auto-pairs' "automatically closes parentheses, square brackets and braces when typing.
Plug 'ap/vim-css-color' 
Plug 'airblade/vim-gitgutter' "Shows Git changes in open files.
Plug 'vim-airline/vim-airline-themes' 
Plug 'morhetz/gruvbox' "Color schemes
Plug 'elvessousa/sobrio' "Color schemes


call plug#end()


nnoremap <C-q> :q! <CR>
nnoremap <F5> :NERDTreeToggle<CR>

let g:NERDTreeShowHidden=1
let g:NERDTreeDirArrowExpandable = '+'
let g:NERDTreeDirArrowCollapsible = '~' 

let g:airline_theme='sobrio'
let g:airline_powerline_fonts = 1
let g:airline#extensions#tabline#enabled = 1

let g:airline_theme='cobalt2'
   
