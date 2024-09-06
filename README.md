![tender](https://cloud.githubusercontent.com/assets/829859/18413534/f7cb472c-77aa-11e6-86bf-9c790aadd2df.png)
==============================================================================================================

A 24bit colorscheme for Vim, Airline and Lightline (generated by [Estilo](https://github.com/jacoborus/estilo))

- [Screenshots](#screenshots)
- [Installation](#installation)
- [Terminal themes](#terminal-themes)

## Screenshots

![javascript](https://cloud.githubusercontent.com/assets/829859/18417365/7780885a-782e-11e6-8e88-150cfc70e35b.png)
![statusplus](https://cloud.githubusercontent.com/assets/829859/18418261/0e0f54f4-7843-11e6-9825-bff197a7f76a.png)
![statusregular](https://cloud.githubusercontent.com/assets/829859/18491051/f81ba21a-7a04-11e6-85c6-e9bc3c98415f.png)
![xml](https://cloud.githubusercontent.com/assets/829859/18494378/1590f654-7a16-11e6-8885-c16a41bf5583.png)
![nerdtree-yaml](https://cloud.githubusercontent.com/assets/829859/18417875/4b3e382e-783c-11e6-94ea-afb9bf0d68f2.png)
![gitcommit](https://cloud.githubusercontent.com/assets/829859/18418089/270b409c-7840-11e6-8618-1aa81f612860.png)
![gvdiff](https://cloud.githubusercontent.com/assets/829859/18417983/3253da42-783e-11e6-93ac-b0f506f0a3c5.png)


## Installation

Install manually or use a package manager:

```viml
" vim-plug
Plug 'jacoborus/tender.vim'
" NeoBundle
NeoBundle 'jacoborus/tender.vim'
" Vundle
Plugin 'jacoborus/tender.vim'
```

Once your plugin is installed you can set the color scheme in your `.vimrc` or `init.vim`


```viml
" If you have vim >=8.0 or Neovim >= 0.1.5
if (has("termguicolors"))
 set termguicolors
endif

" For Neovim 0.1.3 and 0.1.4
let $NVIM_TUI_ENABLE_TRUE_COLOR=1

" Theme
syntax enable
colorscheme tender
```


Use [lightline](https://github.com/itchyny/lightline.vim) themes (`tender` and `tenderplus`):

```viml
" set lighline theme inside lightline config
let g:lightline = { 'colorscheme': 'tender' }
```

Use [airline](https://github.com/vim-airline/vim-airline) themes (`tender` and `tenderplus`):

```viml
" set airline theme
let g:airline_theme = 'tender'
```


Fix for MacVim ([see issue](https://github.com/jacoborus/tender.vim/issues/9)):
```viml
let macvim_skip_colorscheme=1
```

Copy color to vim if no exist `~/.vim/colors/`, create folder.
```
 cp ~/.vim/bundle/tender/colors/tender.vim ~/.vim/colors/tender.vim
```

## Terminal themes

- [Tender Alacritty](https://github.com/huyvohcmc/tender-alacritty) by [@huyvohcmc](https://github.com/huyvohcmc)
- [Tender xresources](https://github.com/pebeto/tender-xresources) by [@pebeto](https://github.com/pebeto)
- [Tender Blink Shell](https://github.com/Rafaelcv7/Jacoborus-Tendertheme) by [@Rafaelcv7](https://github.com/Rafaelcv7)
- [Tender WezTerm](https://github.com/kyoheiu/tender-wezterm) by [@kyoheiu](https://github.com/kyoheiu)
- [Tender Kitty](https://github.com/CompEng0001/tender-kitty) by [@CompEng0001](https://github.com/CompEng0001)

<br><br>

![pacman-tender](https://cloud.githubusercontent.com/assets/829859/19010929/af7489e0-8789-11e6-8c0f-a18055d5b4c4.png)

---

© 2016 Jacobo Tabernero [(jacoborus.codes)](http://jacoborus.codes) - Released under [MIT License](https://raw.github.com/jacoborus/nanobar/master/LICENSE)
