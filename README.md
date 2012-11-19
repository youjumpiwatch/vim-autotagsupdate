This is FORK of http://www.vim.org/scripts/script.php?script_id=1343

Introduction
------------
The "AutoTagsUpdate" plugin is a light vim plugin that could automatically update tags.

Features
--------
  - Delete old entries before updating tags
  - Works asynchronously

Installation
------------
  - Put the plugin folder into ~/.vim

Usage
-----
The plugin is automatically enabled. To disable it, add
leg g:loaded_AutoTagsUpdate=1
to .vimrc

Configuration
-------------
" Don't update tags when the tag file is larger thant 10MB
let g:autotagmaxTagsFileSize = 1024*1024*10
let g:autotagmaxExcludeSuffixes = "tml.xml.text.txt"
let g:autotagmaxVerbosityLevel = logging.WARNING
let g:autotagmaxCtagsCmd = "ctags"
" Set it to 1 to disable it
let g:autotagmaxDisabled = 0
let g:autotagmaxStopAt = 0

