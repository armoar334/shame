# Shame
A pager written in POSIX coreutils and sh

# Usage (currently only supports one file)
```./shame file.txt```
or
```cat file.txt | shame```  
|Keys| |
|--|--|
|Up / Down arrow keys | Scroll up / down by 1 line |
|Left / Right arrow keys | Pan left / right by 4 characters|
|Page Up / Down | Scroll up / down by terminal height lines |
| / | Highlight search |

# Installation
```
$ chmod +x shame
$ mv shame /usr/bin (or anywhere on $PATH)
```
