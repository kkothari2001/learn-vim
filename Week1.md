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
5. There are some vim plugins that help you traverse this complicated tree, I might se them later.

### Deleting stuff
1. In command mode, `x` deletes the current character that you are on. (can be undone with `u`)
2. Deleting an entire line is `dd`. Yes, d is twice, doesn't have to be done quickly.
