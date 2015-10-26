# justifier
A simple text justifier command line tool for vim

# Testing
A test text file is included for testing purposes. Use this to see the magic in action:
```
cat in | ./justifier
```

# Installation
Add this to your .vimrc after copying the file to /usr/local/bin
```
nmap <leader>a :.!justifier -w 80<CR>
vmap <leader>a :!justifier -w 80<CR>

```
