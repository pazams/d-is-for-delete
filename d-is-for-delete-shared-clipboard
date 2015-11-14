"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
" => pazams opinionated- ‘d is for delete’ & ‘ leader-d is for cut’ (shared clipboard register mode)
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""

" if you are using the yankring plugin, there could be some conflicts.
" to make the most of these suggested mappings,
" make sure to delete any keys mapped below from the following line at yankring.vim 
" (i.e. delete 'x' and 'D'):
" let g:yankring_n_keys = 'Y D x X'

nnoremap x "_x
nnoremap X "_X
nnoremap d "_d
nnoremap D "_D
vnoremap d "_d

if has('unnamedplus')
  set clipboard=unnamed,unnamedplus
  nnoremap <leader>d "+d
  nnoremap <leader>D "+D
  vnoremap <leader>d "+d
else
  set clipboard=unnamed
  nnoremap <leader>d "*d
  nnoremap <leader>D "*D
  vnoremap <leader>d "*d
endif
