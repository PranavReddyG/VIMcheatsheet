# __Edit files:__

* "__i__" - To enter insert mode.

* "__Esc__" key or "__Ctrl + [__" - To exit Insert mode.

* "__o__" - Insert a new line below the line containing the cursor.

* "__O__" - Insert a new line above the line containing the cursor.

* "__v__" - Enter Visual Mode.

* "__V__" - Enter Visual Line mode  

* "__Ctrl + V__" - 

* "__:q__" - Quit.

* "__:w__" - Save changes.

* "__:wq__" or "__:x__" or "__ZZ__" - Save changes and quit.

* "__:q!__" - Exit without saving changes.

* "__s__" - To delete the character before the cursor and enter the insert mode.

* "__S__" - To delete a line in which the cursor is placed and enter insert mode.

* "__r__" - Replace a character.

* "__R__" - Enter replace mode.

* "__u__" or "__:u__" or "__:undo__" - Undo.

* "__2u__" - To undo the last 2 changes. 

* "__Ctrl + r__" or "__:redo__" - Redo.

* "__x__" - Delete a single character.

* "__d0__" - Delete text from the starting of the line till the cursor.

* "__d$__" - Delete text after the cursor till the end of the line.

* "__c__" - Change operator.

* "__J__" - Deletes a line break.

* "__Ctrl + n__" - Autocomplete.

* "__:left__" - Align text to the left.

* "__:center__" - Align text to the center.

* "__:right__" - Align text to the right.

* "__:split__" - Splits the current window into two.

* "__:set expandtab shiftwidth=4 softtabstop=4__" - For tab = 4 spaces.


# __Commenting/Uncommenting multiple lines:__

* For commenting multiple lines at once, place the cursor over the first character of the line and press "__Ctrl + v__". Use "__j, k__" or arrow keys to select multiple lines. Then press "__Shift + i__". Now press "__#__" and hit "__Esc__" key twice.

* For uncommenting multiple lines at once, place the cursor over "__#__" and press "__Ctrl + v__". Use "__j, k__" or arrow keys to select multiple lines. Then press "__x__".

# __Clipboard:__

* "__d__" - Cut the selected text.

* "__y__" - Copy the selected text.

* "__dd__" - Delete a line (Cut).

* "__yy__" - Copy the line.

* "__p__" - Paste.

* "__vip__" - Select paragraph.
    > _Usage: Use arrow keys to select the text as required._ 


# __Navigation:__

* "__h__", "__j__", "__k__", "__l__" - Move Left, Down, Up, Right respectively.
 
* "__Ctrl + U__" or "__Ctrl + u__" - Scroll up by half page.

* "__Ctrl + D__" or "__Ctrl + d__" - Scroll down by half page.

* "__Ctrl + E__" - Scroll up by one line.

* "__Ctrl + Y__" - Scroll down by one line.

* "__0__" - Start of the line.

* "__^__" - Start of the non-blank characters in a line. 

* "__$__" - End of the line.

* "__gg__" - Moves to the top of the file.

* "__G__" - Moves to the bottom of the file.

* "__:set number__" - Displays the line number.

* "__:n__" - Goes to n<sup>th</sup> line.

* "__w__" - Moves to the start of the next word.
    > _Usage: Use_ __2w__ _to move the cursor forward by 2 words and place the cursor at the start of the word._

* "__b__" - Moves to the start of the previous word.
    > _Usage: Use_ __2b__ _to move the cursor backward by 2 words and place the cursor at the start of the word._

* "__e__" - Moves to the end of the next word.
    > _Usage: Use_ __2e__ _to move the cursor forward by 2 words and place the cursor at the end of the word._


# __Search:__

* "__:set ignorecase__" - Ignore case.

* "__:set noignorecase__ " - To match case. 

* "__:set hlsearch__" - To highlight all the search matches. 

* "__/__" - Search for a particular word.
    > _Usage:_ ___/Type___ _searches for the word Type._

*        
   
