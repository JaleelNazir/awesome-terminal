
## Terminal shortcuts

### Cut | Copy | Paste

- To copy the text - `CMD + C`
- To cut the text - `CMD + X`
- To paste the text - `CMD + V`
- Print the file - `cat filename`
- Show real updates on log files - `tail -f filename`

### Move the cursor

- Move cursor to first character - `Ctrl + A`
- Move cursor to last character - `Ctrl + E`
- Move cursor to left by one character - `Ctrl + B`
- Move cursor to right by one character - `Ctrl + F`
- Move cursor to left by one word - `alt|option + (Left arrow)`
- Move cursor to right by one word - `alt|option + (Right arrow)`


### Delete character | word

- Delete one character to cursor left - `Delete` or `Backspace`
- Delete one character to cursor right - `Ctrl + D` or `Fn + Delete`
- Delete word to cursor left - `Ctrl + W` or `alt|option + Delete`
- Delete word to cursor right - `Esc` and `D`
- Delete all the words right to the cursor(to EOL) - `Ctrl + K`
- Delete full line - `Ctrl + U`

### Clear Terminal

- Terminate or cancel the command - `Ctrl + C`
- Clear last ran command - `CMD + L`
- Clear screen - `CMD + K`
- Logout the terminal session - `Ctrl + D`

## Vi shortcuts

- To open file for edit - `vi file_name.txt`

### Cursor Commands

- Move left one character - `h`
- Move down one line - `j` 
- Move up one line - `k` 
- Move right one character - `l` 
- Move right one word - `w` 
- Move right one word (past punctuation) - `W` 
- Move left one word - `b` 
- Move left one word (past punctuation) - `B` 
- Move to end of current word - `e` 
- Move down one line - `Return` 
- Move left one character - `Backspace` 
- Move right one character - `Spacebar` 
- Move to top of screen - `H` 
- Move to middle of screen - `M` 
- Move to bottom of screen - `L` 
- Page forward one screen - `Ctrl-F` 
- Scroll forward one-half screen - `Ctrl-D` 
- Page backward one screen - `Ctrl-B` 
- Scroll backward one-half screen - `Ctrl-U` 
- Move cursor to last character of the line - `Fn + (Left arrow)`
- Move cursor to first character of the line  - `Fn + (Right arrow)`

### Inserting Characters and Lines

- Insert characters to right of cursor - `a` 
- Insert characters at end of line - `A` 
- Insert characters to left of cursor - `i` 
- Insert characters at beginning of line - `I` 
- Insert line below cursor - `o` 
- Insert line above cursor - `O`

### Changing Text

- Change word (or part of word) to right of cursor - `cw` 
- Change line - `cc` 
- Change from cursor to end of line - `C` 
- Substitute string for character(s) from cursor forward - `s` 
- Replace character at cursor with one other character - `r` 
- Break line - `r Return` 
- Join current line and line below - `J` 
- Transpose character at cursor and character to right - `xp` 
- Change case of letter (uppercase or lowercase) - `~`
- Undo previous command - `u` 
- Undo all changes to current line - `U` 
- Undo previous last-line command - `:u` 


### Deleting Text

- Delete character at the cursor - `x` 
- Delete character to the left of the cursor - `X` 
- Delete word (or part of word to right of cursor) - `dw` 
- Delete line containing the cursor - `dd` 
- Delete part of line to right of cursor - `D` 
- Delete to end of file - `dG` 
- Delete from beginning of file to cursor - `d1G` 
- Delete lines 5-10 - `:5,10 d` and `Enter`
- Delete all text - `:1, $d` and `Enter`


### Copying and Moving Text

- Yank or copy line - `yy` 
- Yank or copy line - `Y` 
- Put yanked or deleted line below current line - `p` 
- Put yanked or deleted line above current line - `P` 
- Copy lines 1-2 and put after line 3 - `:1,2 co 3` 
- Move lines 4-5 and put after line 6 - `:4,5 m 6`

### Setting Line Numbers

- Show line numbers - `:set nu` 
- Hide line numbers - `:set nonu`

### Setting Case-sensitivity

- Searches should ignore case - `:set ic` 
- Searches should be case sensitive - `:set noic`

### Finding a Line

- Go to last line of file - `G` 
- Go to first line of file - `1G` 
- Go to line 21 - `21G` 

### Searching and Replacing

- Search for **string** - `/string`
- Search backward for **string** - `?string`
- Find next occurrence of **string** in search direction - `n`
- Find previous occurrence of **string** in search direction - `N`
- Search and replace - `:g/search/s//replace/g`

### Clearing the Screen

- Clear (refresh) scrambled screen - `Ctrl-L` 

### Inserting a File Into a File

- Insert (read) file after cursor - `:r filename` 
- Insert file after line 34 - `:34 r filename` 

### Saving and Quitting

- Save changes (write buffer) - `:w` 
- Write buffer to named file - `:w filename` 
- Save changes and quit vi - `:wq` 
- Save changes and quit vi - `ZZ` 
- Quit without saving changes - `:q`
- Force quit vi without saving changes - `:q!` 


# Todo:

- [ ] VISUAL BLOCK
  - [ ]  Comment multiple lines 
- [ ] Screen
- [ ] Git
- [ ] Nano
- [ ] Network commands
- [ ] Search by process name
- [ ] Search by process port
- [ ] Stop process by process id
- [ ] Stop process by process name
- [ ] Curl
- [ ] telnet
- [ ] dig
- [ ] File permissions - chmod & chmown
- [ ] ssh
- [ ] scp
- [ ] Security groups
- [ ] Update to network UTC time
- [ ] NGINX
- [ ] SUPERVISOR
- [ ] MYSQL
- [ ] REDIS
- [ ] Memcache
- [ ] Celery Flower


# Thanks

## References: 

- https://stackoverflow.com/questions/657130/fastest-ways-to-move-the-cursor-on-a-terminal-command-line
- https://superuser.com/questions/362113/how-to-delete-all-characters-after-cursor-in-shell
- https://docs.oracle.com/cd/E19253-01/806-7612/editorvi-tbl-83/index.html