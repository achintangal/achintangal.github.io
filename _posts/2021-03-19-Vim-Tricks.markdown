---
layout: post
title:  "Vim Tricks"
date:   2021-03-19 02:20:19 -0700
categories: vim 
---

As Vim is my goto editor for most things, I have listed out things I have added
to my vim config. 

- Spellcheck 
- Markdown Support
- Shortcuts

{% highlight bash %}
set number
set laststatus=2
set ruler 
set wildmenu
autocmd BufRead,BufNewFile *.markdown setlocal spell

{% endhighlight %}


