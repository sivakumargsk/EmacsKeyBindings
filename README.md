### Emacs Commands List

[Original Post](http://www.ast.cam.ac.uk/~vasily/idl/emacs_commands_list.html)

> C = Control,   M = Meta = Alt|Esc

#### Basics
| Key Binding   | Description   |
| ------------- |-------------|
|`C-x C-f` | "find" file i.e. open/create a file in buffer|
|`C-x C-s` | save the file|
|`C-x C-w` | write the text to an alternate name|
|`C-x C-v` | find alternate file|
|`C-x i  ` | insert file at cursor position|
|`C-x b  ` | create/switch buffers|
|`C-x C-b` | show buffer list|
|`C-x k  ` | kill buffer|
|`C-z    ` | suspend emacs|
|`C-X C-c` | close down emacs|

#### Window-Commands

| Key Binding  | Description |
| -------------|-------------|
|`C-x 2` | split window vertically |
|`C-x o` | change to other window |
|`C-x 0` | delete window |
|`C-x 1` | close all windows except the one the cursors in |
|`C-x ^` | enlarge window |
|`M-x` | shrink-window command says it ;-) |
|`M C-v` | scroll other window |
|`C-x 4 f` | find file in other window |
|`C-x 4 o` | change to other window |
|`C-x 4 0` | kill buffer and window |
|`C-x 5 2` | make new frame |
|`C-x 5 f` | find file in other frame |
|`C-x 5 o` | change to other frame |
|`C-x 5 0` | close this frame |


#### Important

| Key Binding | Description|
|-------------|------------|
|`C-g` | quit the running/entered command |
|`C-x u` | undo previous action |
|`M-x revert-buffer RETURN` | (insert like this) undo all changes since last save |
|`M-x recover-file RETURN` | Recover text from an autosave-file |
|`M-x recover-session RETURN`| if you edited several files |

#### Basic movement

| Key Binding   | Description   |
| ------------- |-------------|
|`C-f` | forward char|
|`C-b` | backward char|
|`C-p` | previous line|
|`C-n` | next line|
|`M-f` | forward one word|
|`M-b` | backward one word|
|`C-a` | beginning of line|
|`C-e` | end of line|
|`C-v` | one page up|
|`M-v` | scroll down one page|
|`M-<` | beginning of text|
|`M->` | end of text|
|      | ** Works For Pervez sir's init.el file **|
|`C-s-up` | Buffer move up |
|`C-s-down' | Buffer move down |
|`C-s-left` | Buffer move left |
|`C-s-right' | Buffer move right |


#### Editing

| Key Binding   | Description   |
|------------- |------------|
|`M-n` | repeat the following command n times |
|`C-u` | repeat the following command 4 times |
|`C-u` | n repeat n times |
|`C-d` | delete a char |
|`M-d` | delete word |
|`M-Del` | delete word backwards |
|`C-k` | kill line |
|`C-Space` | Set beginning mark (for region marking for example) |
|`C-W` | "kill" (delete) the marked region region |
|`M-W` | copy the marked region |
|`C-y` | "yank" (paste) the copied/killed region/line |
|`M-y` | yank earlier text (cycle through kill buffer) |
|`C-x` | C-x exchange cursor and mark |
|`C-t` |  transpose two chars |
|`M-t` |  transpose two words |
|`C-x C-t` | transpose lines |
|`M-u` |  make letters uppercase in word from cursor position to end |
|`M-c` |  simply make first letter in word uppercase |
|`M-l` |  opposite to M-u |

#### Multiple Cursors

| Key Binding | Description|
|-------------|------------|
|`C-<`  | mark previous like this|
|`C->`  | mark next like this|
|`C-c C-<` | mark all like this|
|`C-c c r` | set rectangular region anchor|
|`C-c c c` | edit lines|
|`C-c c e` | edit ends of lines|
|`C-c c a` | edit beginnings of lines|

#### Search/Replace

| Key Binding   | Description |
| ------------- |-------------|
|`C-s` | Search forward |
|`C-r` | search backward |
|`C-g` | return to where search started (if you are still in search mode) |
|`M-%` | query replace |
|      | `Space` or `y` replace this occurence <br> `Del` or `n` don't replace <br> `.`  only replace this and exit (replace) <br> `,`  replace and pause (resume with Space or y) <br> `!`  replace all following occurences <br> `^`  back to previous match <br> ``RETURN`` or `q` quit replace |

#### Search/Replace with regular expressions

> Characters to use in regular expressions:

| Key Binding   | Description |
| ------------- |-------------|
|`^` | beginning of line|
|`$` | end of line|
|`.` | single char
|`.*`| group or null of chars|
|`\<`| beginning of a word|
|`\>`| end of a word |
|`[]`| every char inside the backets (for example [a-z] means every small letter)}|
|`M C-s RETURN` | search for regular expression forward |
|`M C-r RETURN` | search for regular expression backward |
|`M C-s` | incremental search |
|`C-s` | repeat incremental search |
|`M C-r` | incremental search backwards |
|`C-r` | repeat backwards |
|`M-x` | query-replace-regexp search and replace |



#### Version Control

| Key Binding | Description |
|-------------|-------------|
|`C-x v d` | show all registered files in this dir |
|`C-x v =` | show diff between versions |
|`C-x v u` | remove all changes since last checkin |
|`C-x v ~` | show certain version in different window |
|`C-x v l` | print log |
|`C-x v i` | mark file for version control add |
|`C-x v h` | insert version control header into file |
|`C-x v r` | check out named snapshot |
|`C-x v s` | create named snapshot |
|`C-x v a` | create changelog file in gnu-style |


#### Bookmark commands

| Key Binding  | Description |
| -------------|-------------|
|`C-x r m` | set a bookmark at current cursor pos |
|`C-x r b` | jump to bookmark |
|`M-x bookmark-rename`| says it |
|`M-x bookmark-delete`| says it |
|`M-x bookmark-save`  | says it |
|`C-x r l` | list bookmarks |
|        | `d` mark bookmark for deletion <br> `r` rename bookmark <br> `s` save all listed bookmarks <br> `f` show bookmark the cursor is over <br> `m` mark bookmarks to be shown in multiple window <br> `v` show marked bookmarks (or the one the cursor is over) <br> `t` toggle listing of the corresponding paths <br> `w` " path to this file <br> `x` delete marked bookmarks <br> `Del` ? <br> `q` quit bookmark list|
|`M-x bookmark-write` | write all bookmarks in given file|
|`M-x bookmark-load` | load bookmark from given file|

#### Shell

| Key Binding | Description |
|-------------|-------------|
|`M-x` | shell starts shell modus |
|`C-c C-c` | same as `C-c` under unix (stop running job) |
|`C-d` | delete char forward |
|`C-c C-d` | Send EOF |
|`C-c C-z` | suspend job (`C-z` under unix) |
|`M-p` | show previous commands |

#### Text
> Works only in text mode

| Key Binding | Description |
|-------------|-------------|
|`M-s` | center line |
|`M-S` | center paragraph |
|`M-x` | center-region name says |

#### Macro-commands

| Key Binding | Description |
|-------------|-------------|
|`C-x (` | start macro definition |
|`C-x )` | end of macro definition |
|`C-x e` | execute last definied macro |
|`M-n C-x e` | execute last defined macro n times |
|`M-x name-last-kbd-macro` | give name to macro (for saving) |
|`M-x insert-keyboard-macro` | save named macro into file |
|`M-x load-file` | load macro |
|`M-x macroname` | execute macroname |


#### DIRectory EDitor (dired)

| Key Binding | Description |
|-------------|-------------|
|`C-x d` | start up dired |
|        |`C` (large C) copy <br>`d` mark for erase <br>`D` delete right away <br>`e` or `f` open file or directory <br>`g` reread directory structure from file <br>`G` change group permissions (chgrp) <br>`k` delete line from listing on screen (don't actually delete) <br>`m` mark with \* <br>`n` move to next line <br>`o` open file in other window and go there <br>`C-o` open file in other window but don't change there <br>`P` print file <br>`q` quit dired <br>`Q` do query-replace in marked files <br>`R` rename file <br>`u` remove mark <br>`v` view file content <br>`x` delete files marked with D <br>`z` compress file <br>`M-Del` remove all marks (whatever kind) <br>`~` mark backup files (name~ files) for deletion <br>`#` mark auto-save files (#name#) for deletion <br>`*/` mark directory with \* (C-u \* removes that mark again) <br>`=` compare this file with marked file <br>`M-=` compare this file with it's backup file <br>`!` apply shell command to this file <br>`M-}` change to the next file marked with \* od D <br>`M-{` change to the previous file marked with \* od D <br>`% d` mark files described through regular expression for deletion <br>`% m` mark files described through regular expression for deletion (with \*) <br>`+` create directory <br>`>` changed to next dir <br>`<` change to previous dir <br>`s` toggle between sorting by name or date|

#### Telnet
| Key Binding | Description |
|-------------|-------------|
|`M-x` | telnet starts up telnet-modus |
|`C-d` | either delete char or send EOF |
|`C-c C-c` | stop running job (similar to C-c under unix) |
|`C-c C-d` | send EOF |
|`C-c C-o` | clear output of last command |
|`C-c C-z` | suspend execution of command |
|`C-c C-u` | kill line backwards |
|`M-p` | recall previous command |



#### Programming

| Key Binding | Description |
|-------------|-------------|
| `M C-\` | indent region between cursor and mark |
| `M-m` | move to first (non-space) char in this line |
| `M-^` | attach this line to previous |
| `M-;` | formatize and indent comment |
|      | C, C++ and Java Modes |
| `M-a` | beginning of statement |
| `M-e` | end of statement |
| `M C-a` | beginning of function |
| `M C-e` | end of function |
| `C-c RETURN` | Set cursor to beginning of function and mark at the end |
| `C-c C-q` | indent the whole function according to indention style |
| `C-c C-a` | toggle modus in which after electric signs (like {}:';./\*) emacs does the indention |
| `C-c C-d` | toggle auto hungry mode in which emacs deletes groups of spaces with one del-press |
| `C-c C-u` | go to beginning of this preprocessor statement |
| `C-c C-c` | comment out marked area |
|           | More general (I guess) |
| `M-x outline-minor-mode` | collapses function definitions in a file to a mere {...} |
| `M-x show-subtree` | If you are in one of the collapsed functions, this un-collapses it In order to achive some of the feats coming up now you have to run etags \*.c \*.h \*.cpp (or what ever ending you source files have) in the source directory |
| `M-. (Thats Meta dot) `  | If you are in a function call, this will take you to it's definition |
| `M-x tags-search ENTER` | Searches through all you etaged |
| `M-, (Meta comma)` | jumps to the next occurence for tags-search |
| `M-x tags-query-replace` | yum. This lets you replace some text in all the tagged files |


#### GDB (Debugger)
| Key Binding | Description |
|-------------|-------------|
|`M-x gdb` | starts up gdm in an extra window|

#### Online-Help

| Key Binding   | Description   |
| ------------- |------------|
|`C-h c` | which command does this keystroke invoke |
|`C-h k` | which command does this keystroke invoke and what does it do? |
|`C-h l` | what were my last 100 typed keys |
|`C-h w` | what key-combo does this command have? |
|`C-h f` | what does this function do |
|`C-h v` | what's this variable and what is it's value |
|`C-h b` | show all keycommands for this buffer |
|`C-h t` | start the emacs tutorial |
|`C-h i` | start the info reader |
|`C-h C-k` | start up info reader and go to a certain key-combo point |
|`C-h F` | show the emacs FAQ |
|`C-h p` | show infos about the Elisp package on this machine |