# vim-opengl-syntax

OpenGL syntax highlighting for C and C++ files in Vim.

## Installation

- If you want Vim to automatically load the syntax file for all `c` and `cpp`
  files, clone this repository into a directory under `~/.vim/pack/*/start/`,
  where `*` can be _any_ directory name. Example:
  ```bash
  $ cd ~/.vim/pack/github-plugins/start
  $ git clone https://github.com/bfrg/vim-opengl-syntax
  ```
- If you prefer to manually load the syntax file only when working on a OpenGL
  project, clone this repository into `~/.vim/pack/*/opt/`, where `*` can be
  _any_ directory name. Example:
  ```bash
  $ cd ~/.vim/pack/github-plugins/opt
  $ git clone https://github.com/bfrg/vim-opengl-syntax
  ```
  Whenever you work on an OpenGL project, run `:packadd vim-opengl-syntax`, and
  reload any already opened `c` or `cpp` files.

See `:help packages` and `:help :packadd` for more details.

Alternatively, use your favorite plugin manager.
