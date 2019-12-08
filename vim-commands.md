# How to use Vim 
This document has notes on how to use vim/vi editor. 

[Vim CheatSheet](https://vim.rtorr.com)

Plan 
1. Learn the basics 75 commands are good enough 
2. Keep a cheat sheet 
3. Keep learning new things.

### Movement keys in normal mode 
* h - left one character 
* j - down one line 
* k - up one line 
* l - right one character l
* w - move one word at time [forward]
* b - move one word at a time [backword]
* e - move one word at a time but move to the last character of the word. 
* H - move to the top of the file 
* M - move to the middle of the file 
* L - move to the bottom of the file. 

### Searching and find 
* / followed by the word or pharase you are looking for will serach for all occurances of the word. 
* n - once the search has happened to move to the next occurrance press n. 
* cntl+o - this will take you to the previous occurance of the phrase you were looking for. i
* % - is used for matching brackets or paranthesis and all of the bracket [, '{', (, will be matched. 

### Substitution command 
* :s/old/new/g - this will replace the 'old' with 'the' new string globally because of the /g at the end if we remove the /g it only does this for the current line.
* :#,#s/old/new/g - substitute between line numbers speficied by # and #.    

### Verbs and Nouns 
* d - delete verb will wait for the next operation and to delete  dw will delete a word you are on and dd will delete the entire line. 
	* d$ - this command will detele the entire line form the current cursor position to the end of the line. 
	* dw - deletes a word that you are currently on. 
	* dW - will delete words that have hyphens or periods them too.
* c - stands for change c [number] motion therefore cw means change till the end of the word mentioned below too. or c$ meaning delte the rest of the line and insert. 
	* ce - will delete the word and place you into insert mode. 
	* c$ - change till end of the line (delete) and insert mode. 
* p - paste the content that has been copied.
* r - replaces a character under the current cursor so 're' will replace the current cursor position with e similar ru repleaces the current character with u
* ~ - will toggle the case of the character the cursor is on. Therefore the lower case character will become uppercase and vice versa. 

### Screen movement 
* zz - centers the cursor location in a large file. it allows for you to see some portions above and below the cursor
* cntl+e - will move the line above but keep the cursor at the same position. 
* cntl+y - will do the opposite will move the screen down and keep the cursor at the same position. 
* cntl+f - will move down one screen lenght at a time. 
* mm - sets a mark in a file and then you can move around in a file and if you want to come back to it you can do `m to come back  
* gg -  n gg will take you to the line number that is give by n. just typing gg will move to the first line. 
* G - go to the last line of the file. 5G would take you to line 5 
* fx - jump to the next occurance of the character x. 
* } - jump to the next paragraph. 
* '{' - jump to the previous paragraph.  

### Movement within a line 
* 0 -  will take you to the start of the line  
* $ - will take you to the end of the line 
* '*' - is a command that will take you to the next occurance of the word that you are on. 
* '#' - is command will do the same thing as '*' but will do it in reverse.

### Tabs 
* :tabnew or :tabnew file - will open a new tab 
* gt - move to the next tab or #gt to go to the tab with that number. 
* gT - move to the previous tab. 
* :tabclose - will close to the windows.  

