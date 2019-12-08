# Vim Language 
The notes here come form a talk in youtube by thoughtbot 

## Syntax 
The vim syntax is -  **verb + noun** - verb stands for an operation and noun is 
the entity on which the operation has to be performed.
examples: 
* dw  - d stands for delete verb and the w is the object which stands for words
* d$  - delete is the verb and the $ stands till the end of the line. 

## Verbs 
* d - delete 
* c - change which stands for a delete and then goes insert mode this too requies an object at the end.
* > - indent will indent the text and < will outdent the text  
* v - will help select a text visually.
* y - stands for yank or copy the operator will again take nouns at the end. 
* . - repeats the last command from the cursor position. 

## Nouns in Vim - motion 
* w - stands for word and it moves forward at the start of the next word. 
* b - stands for back and this moves back one word at a time 
* e - moves forward by one work but to the last character of the word
* j - down motion 
* k - up motion 
* { - move to the previous paragraph 
* } - move to the next paragraph 
* L - move you to the last line of your screen 
* zz - centers the line that you are on to the middle of the screen 
* ctl+e - scrolls the screen down keeping the cursor at the same place 
* ctl+y - scrolls the screen up keeping the cursor at the same place 
* ctl+d - move down half a screen length at a time 
* ctl+u - move up half a screen length at a time 
* ctl+f - move one full screen forward 
* ctl+b - move back one full screen length at a time

## Nouns in Vim - text objects 
working with tags, words, paragraphs 
* iw - "inner word" (works from anywhere in the word) this can be a object of verbs mentioned above. 
* it - "inner tags" (content withing the tags) 
* i"  - "inside quotes" 
* ip  - inside paragraphs 
* as - a sentence 

## Nouns in Vim - parameterized text objects 
* f,F -find the next occurance of the character
    * so we can put a verb before the f to get next occurance like dfw will delete the line until the next occurance of w 
* t,T - find the next occurance of character and place the cursor before the character
    * so we can put a verb before the t. 'ctL' will delete the content till, but not including,the next occurance of L 
* / - search up to the next match. 

## Insert Operations in Vim 
* S - delete the line that you are on and begin insert at the same line
* C - delete all the content to the end of the line and start insert mode.- this is equal to c$ 
* A - enter insert mode at the end of the line 
* a - enter insert mode after the cursor position. 
