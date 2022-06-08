# Week 1

## Day 1
I had some prior knowledge with vim, but only upto basic text insertion and navigation using the h,j,k,l keys. This allowed me to atleast get started with this repository with only vim/CLI.
Things I learnt:
1. Writing to a file using `:w <filename>`
2. Saving open file using `:w`
3. Quitting after saving using `:wq`
4. Quitting without saving using `:q!`
5. Simple quitting using `:q`
6. Going into insert mode with `i`
7. Going into insert mode with `a` (starts entering chars from the next charachter)
8. going into insert mode with `shift+a` (starts entering charachters from the end of the current line)

I will continue some practise with it, till I become good at typing with it easily.

## Day 2
Couldn't practise much.

## Day 3
Continued to second video of the tutorial series from [LearnLinuxTV](https://www.youtube.com/c/LearnLinuxtv), uptill now, navigation is difficult and it is tedious to navigate one letter at a time, I will have to look for a better alternative. Copy paste is alsosomething I'm not very sure about. Currently the shortcut to paste text into my terminal emulator seems to work well, but I'm sure there is a better (more Vim-like) way to do this same task.

Things I learnt:
### Basics of undoing and redoing things
1. Undo in vim is `u`. undo usually undoes everything you typed the last time you were in `INSERT` mode. (Note: `u` also undoes single commands)
2. To undo multiple changes, we can use `nu` where n is a number. e.g `2u` is equivalent to doing u twice.
3. `Ctrl+R` is redo, it brings back the latest changes that you undid.
4. **Undo tree** in vim is very very powerful, so be careful of accidentally going wrong too.
5. There are some vim plugins that help you traverse this complicated tree, I might see them later.

### Deleting stuff
1. In command mode, `x` deletes the current character that you are on. (can be undone with `u`)
2. Deleting an entire line is `dd`. Yes, d is twice, doesn't have to be done quickly.


## Day 4
One thing that I have realised is slowing me down a lot in vim is the extremely slow navigation in a file. I currently only use the `hjkl` keys and `shit+a` for navigating through the entire file, and I feel I can things much faster. so today I am going away from the standard vim tutorial followed so far and going through videos that only focus on the navigation aspect.

Things I learnt:
**Vertical navigation**
1. Moving viewport down by half a page, `ctrl+d` (also moves cursor)
2. Moving viewport up by half a page, `ctrl+u` (also moves cursor)
3. `{` which is equivalent to `shift+[`, moves cursor to the first empty line above the current cursor position. ( **Empty** means just one newline char, not even whitespace chars are allowed.)
4. Same thing with `}` but now you go down to the first empty line.'
5. **Remember** like most commands in vim, typing a number in vim can be preced by a number to make them repeat multiple times. So `5j` goes down 5 lines.
6. `gg` takes cursor to the very start of the file.
7. `shift+g` or `G` will take you to the end of the file. (Cursor will be on the the first char of the last line).

**Horizontal Navigation**
1. `0` to move cursor to start of the line.
2. `$` to move cursor to end of the line.
3. `Shift+i` is insert at the start of the line, just like `shift+a` is insert at the end of the line.
4. `w` goes to the start of the next word.
5. `b` goes to the start of the prev word.

I'm guessing this much is enough for today. I also setup my vimrc in `~/.vim/vimrc` and am remapping my arrow keys to <nop> so I can learn to use `hjkl` effectively. That is done using the following commands.
```
nnoremap <up> <nop>
nnoremap <down> <nop>
nnoremap <left> <nop>
nnoremap <right> <nop>
```

## Day 5
Nothing much done today, I was only using a vim for normal text editing today and applied everything I learnt so far. I often confuse `gg` and `G`. I guess that will be solved with practise.

## Day 6
Nothing much today either, made some changes to the config files and learnt a bit about vim plugins etc.

## Day 7
I use it extensively for my note taking now, I am pretty used to the commands now and have been practising a lot. Also, the `CapsLock` key is a nightmare, but on googling further, many vim users could be found cursing it. So I guess, I'm on the right track. :)
