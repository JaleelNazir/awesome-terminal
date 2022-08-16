## Terminal shortcuts
---
### Cut | Copy | Paste

- to copy the text - `&#8984; CMD + C`
- to cut the text - `&#8984; CMD + X`
- to paste the text - `&#8984; CMD + V`

---

### Move the cursor
- Move cursor to first character - `Ctrl + A`
- Move cursor to last character - `Ctrl + E`
- Move cursor to left by one character - `Ctrl + B`
- Move cursor to right by one character - `Ctrl + F`
- Move cursor to left by one word - `alt|option + &#8592; (Left arrow)`
- Move cursor to right by one word - `alt|option + &#8594; (Right arrow)`

---

### Delete character | word

- Delete one character to cursor left - `Delete` or `Backspace`
- Delete one character to cursor right - `Ctrl + D` or `Fn + Delete`
- Delete word to cursor left - `Ctrl + W` or `alt|option + Delete`
- Delete word to cursor right - `Esc` and `D`
- Delete all the words right to the cursor(to EOL) - `Ctrl + K`
- Delete full line - `Ctrl + U`

### Clear Terminal

- Terminate or cancel the command - `Ctrl + C`
- Clear last ran command - `&#8984; CMD + L`
- Clear screen - `&#8984; CMD + K`
- Logout the terminal session - `Ctrl + D`

## Vi shortcuts

---

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





- Delete one full line 
- Clear full line & insert mode
- Quit vi without save
- Force quit vi without save
- Quit vi with save

### Delete multiple lines 

### Move cursor to last character of the line
### Move cursor to first character of the line
### Move cursor by word to left
### Move cursor by word to right
### Move cursor by line number

### Search by word

### Comment multiple lines with VISUAL BLOCK

### Screen
### Git

- Print the file
- Show real updates on log files
- 



## Nano

---


## Network commands

---

### Search by process name
### Search by process port
### Stop process by process id
### Stop process by process name
### Curl
### telnet
### dig
### chmod
### chmown
### ssh
### scp
### security groups
### Update to network UTC time



## Apps

---

### NGINX
### SUPERVISOR
### MYSQL
### REDIS
### Memcache
### Celery Flower



# Thanks


https://stackoverflow.com/questions/657130/fastest-ways-to-move-the-cursor-on-a-terminal-command-line
https://superuser.com/questions/362113/how-to-delete-all-characters-after-cursor-in-shell


https://docs.oracle.com/cd/E19253-01/806-7612/editorvi-tbl-83/index.html