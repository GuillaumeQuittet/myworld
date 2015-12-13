# Here is  my Tmux and Vim configuration

## My shorcuts used in Vim

> What is the mapleader key in my configuration ?

    <Leader> = ,

### Control the buffer
    <Leader>bn : Switch to the next buffer
    <Leader>bp : Switch to the previous buffer
    <Leader>bf : Switch to the first buffer
    <Leader>bd : Delete the current buffer

### CTags

> What is the shortcut key ?

    <Leader>tt

> Ctags doesn't work

*It's normal because you need to install the exuberant-ctags package.*

### Take the control over your git files
    <Leader>gs : Show the current status of your git repository
    <Leader>ga : Add all the files to your git repository
    <Leader>gc : Send the commit
    <Leader>gp : Push all the files that were added before


### Emmet
> What is the shortcut key ?

> In insert mode

    <C-y>, : Execute emmet

Type this in insert mode :

    html:5

Press the shortcut key in insert mode and your code will be like this

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title></title>
</head>
<body>

</body>
</html>
```

### Fix the indentation
> In normal mode

    <Leader>fi : Fix the indentation in all your file
        ==     : Fix the indentation of the selected line
> In visual mode

    = : Fix the indentation of the selected text

### Disable the highlight after research
    <C-h> : No Hightlight

### Markdown Preview

> How to configure this plugin ?

It's very easy ! Just copy and paste this in your terminal :

    # apt-get install npm
    # npm -g install instant-markdown-d
    # apt-get install xdg-utils

* '#' means "Run this command as root"
* xdg-utils is installed by default on ubuntu
* I use the apt-get package manager but you can do it with yum, pacman and any
  package manager.

### NERDCommenter
> What is the shortcut ?

    <Leader>c<space>

* In normal mode, it will comment the current line.
* In visual mode, it will comment the selected block.

### NERDTree Shorcuts
    <Leader>e : NERDTree toggle
    <C-e>     : NERDTree find

### Numbers.vim
    <F3> : Toggle the numbers
    <F4> : Enable/Disable the numbers

### Paste shorcuts
    <Leader>p  : Enable the paste mode
    <Leader>np : Disable the paste mode

### Sparkup      : HTML ZenCoding
> How I can use this plugin ?

Write your code like this :

    html > body > h1 > div

Then execute sparkup in insert mode like this
> In insert mode

    <Leader>se : Execute sparkup
    <Leader>sn : Next mapping of sparkup

Now, your code is like this

```html
<html>
    <body>
        <h1>
            <div></div>
        </h1>
    </body>
</html>
```

### TagBar
    <Leader>tt : Toggle the tagbar

### Trailing space
> In normal mode

    <Leader>fs : Fix all the white spaces

> In visual mode

    <Leader>fs : Fix the white spaces over the selected text

### Undo tree
    <Leader>u : Toggle the undo tree

### Useful shortcut
    <C-s> : Save the current file
    <C-q> : Exit the file after a save

> If you want to exit without save your file

    :q!


## My Tmux Shortcuts :

> (In Building)