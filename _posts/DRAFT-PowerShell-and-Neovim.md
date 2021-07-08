---
layout: post
title: "A Simple Neovim Setup for Dotnet Core Development"
description: "A guide and sample configuration for setting up a basic Neovim installation on windows for dotnet development."
category: articles
tags: [vim, neovim, dotnet]
comments: false
---

I have recently made the call to move to Neovim for my daily development. I 
have had several false dawns with vim over the years which didnt really end 
in me using vim full time. For a while now I have been using VsVim with VSCode,
that has got my vim fun to a level where I think I can stay productive in a full
time Neovim environment. 

Having been very comfortable with my mouse, VS Code, VsVim here was my wish 
list for my Neovim install:
 - Tab code completion 
 - Omnisharp
 - Integrated Powershell terminal
 - File system browser 
 - Ctrl + . (in the VSCode sense)

So with this in mind let's jump in with the issue that took me the longest to
solve. Omnisharp ... 


{% highlight vim %}
 call plug#begin()
 Plug 'https://github.com/OmniSharp/omnisharp-vim'
 Plug 'https://github.com/ctrlpvim/ctrlp.vim'
 Plug 'https://github.com/preservim/nerdtree'
 Plug 'https://github.com/tpope/vim-commentary'
 call plug#end()
{% endhighlight } 
