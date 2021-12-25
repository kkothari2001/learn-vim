# Week 3

## Day 1
Sory, for missing out for a few days. Now we learn to switch between files in vim. Without actually minimizing vim or sending stuff to the background.

In vim, we don't directly edit files, we edit something called as buffers that are temporary places were you can store your files. These buffers only write to files when you run the `:w` command or any of its variants.

Things I learnt:
1. In Week 2, day 3 we learn about the `:e <filename>` command that is used to open new files. But what we didn't realise is that this only opens another `buffer`.
2. run `:buffers` to view the list of open buffers.
3. You can switch buffers by entering `:b<n>` where <n> is the number of the particular buffer in the `:buffers` list.
4. Buffer numbers don't change, so you can easily remember what buffer you want to change to.
5. By default, you can't quit a buffer before writing it.

