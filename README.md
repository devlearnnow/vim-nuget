## Purpose

To enable NuGet integration in vim.

## Installation

Install using your favourite plugin manager,
I use [vim-plug](https://github.com/junegunn/vim-plug)

`Plug 'markwoodhall/vim-nuget'`

## Requirements

vim-nuget makes use of [vim-webapi](https://github.com/mattn/webapi-vim), [fzf.vim](https://github.com/junegunn/fzf.vim), and [deoplete](https://github.com/Shougo/deoplete.nvim).


```viml
Plug 'mattn/webapi-vim'
Plug 'junegunn/fzf.vim'
Plug 'Shougo/deoplete.nvim'
```

## Commands

`:SearchPackages query`

![search-packages](http://i.imgur.com/yGSHOj8.gif)

`:InstallPackage package` tab completion is available on the package name.

![install-package](http://i.imgur.com/mDSiChI.gif)

`:RemovePackage package` tab completion is available on the package name.

![remove-package](http://i.imgur.com/Q5j83FU.gif)

## Completion

You can also get package name and version completion in `.csproj` files.

![completion](http://i.imgur.com/Y6WlADL.gif)

## License
Copyright © Mark Woodhall. Distributed under the same terms as Vim itself. See `:help license`
