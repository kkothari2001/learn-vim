# Week 2

## Day 1
I had have been using vim for quite some time now and have gotten used to many of the commands used. I tried switching tonvim because that was supposed to be a better overall experience. But updating alternative and all the stuff was a little confusing so I ended up not doing that. I also tried making major changes to my vimrc but realised that my basics are not good enough to be edit and make large changes easily enough.

Things I learnt:
1. `:r <filename>` appends the contents of the other file to the currently open file. The content is appended to the line after the current line (which the cursor is on).
2. Backgrounding vim, use the job control feature of Linux.
    1. `jobs` command lists the current jobs.
    2. `Ctrl+Z` suspends a current job.
    3. `fg` brings the brings the last job back into action.
    4. `fg <number>` (in Bash) and `fg %<number>` (in Zsh) brings back the job with teh particular number. The number denotes the number in square brackets when you type the `jobs` command.
3. Commands in vim itself, you can use `:! <command>` in order to input a command that will be run on the shell.
4. Stuff can be changed using `c` followed by a modifier like `h j k l w e b` to remove everything untill the specified modifier and then put you in INSERT mode so you can change that text.
5. There is some discrepancy in `cw` as it is trated the same as `ce`. This is not a bug, just a special case. I'm glad I'm practising enough to be able to find such special cases on my own. Having to google and finding many many people with the same question is just plain satisfying. :)
6. `Shift+x` or `X` deletes the charachter before the cursor.
7. Now the letter `d` is just like letter `c` but we use d when we intend to delte something and not just change it. Therefore, `c` puts you in the INSERT mode whereas `d` doesn't. `d` just deletes.
8. However d has the same modifiers as c, eg. `h j k l w e b` with the same meaning as that of the movement specifiers. ( No special cases as far as I know)
9. Just how `dd` deletes a line, `cc` changes the entire line.
10. `shift+d` deletes till the end of the line, `shift+c` changes to the end of the line.

I realise I need more pracitse on working with `w b e` but I'm hoping it comes with practise.
I also just switched to nvim, it is not as difficult as I thought XD.

## Day 2
I didn't do much today, just worked with nvim a bit and setup `vim-plug` and installed a few basic plugins. I also realise that nvim has some better inbuilt features than just vim. So that's nice. I also learnt about the colourscheme and decided on the `dracula` theme.

## Day 3
I have not been able to do much, and even not able to log everything I learnt. Currently I am just daily driving vim for all the markdown notes that I take. I also explored a lot with some plugins.

Things I learnt:
1. `:e <filename>` opens that particular file in vim.
2. In vim, copying is called `yanking`. This functionality can be used with the `y` key with a suitable modifier.
3. The opposite of this is pasting, through `p`.

## Day 4
Day 3 parts are still pending. Will contnue them some other day, but right now I am focussing on navigating directories with vim.

Skipped a few days, so lets just assume that didn't happen ????

## Day 3 continued and Day 5
After some minor setbacks, I'm back to practising Vim and working on things I want to develop skills in. I will continue till I am able to daily drive easily in Vim.

Thing I learnt today:
1. We continue with the use of `y` to yank and `p` to paste.
2. `yy` yanks the entire line, just like how `dd` deletes the line.
3. However `shift+y` does not yank to the end of the line, like `shift+d` (which does delete fom current position to the end of the line). I don't like this and might change the mapping in the vimrc. Instead `shift+y` behaves exactly like `yy`!!

