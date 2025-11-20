1. No need to write :w to save the text  
2. No need to press `a`/`s` button to start insert mode
3. Autocomplete to get pairs for `()` etc; to `#include` etc
4. Highlight all the file
5. Easy way to quit all the open files of vim (opened with `vim -p file1 file2...`) and save all the changes
6. Show whitespaces in text. Usefull if writing with norminette
7. Auto-alignment of code
8. Add number of line in file
9. Easy switch between files with `Ctrl+➡️ ` and `Ctrl+⬅️ ` instead of `gt` and `gT` (after opening with `vim -p file1 file2 ...`)
10. Add header42 to every new file (with the specified extension). Work with files created with `vim file`, `touch file` etc
11. Specify default login and email for a header42
12. Find a word and replace it with other word. Make changes in all files at the same time, that are currently opened with `vim -p file1 file2...`:
	- Space+r
	- write a word to replace - enter
	- write a new word - enter
13. Unable placing a mouse somewhere in insert mode
14. Search the words in all files in the specified directory (even in subdirectories)
	with `Space+s`
	to exit after the showing of the result `Ctrl+C`
	*need to install vim-plug:
		```curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    			https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
    		```
		- put the scrip
		- :PlugInstall
