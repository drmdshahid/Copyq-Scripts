# Copyq-Scripts
A few [copyq](https://github.com/hluk/CopyQ) command scripts.

## Quicksave
Purpose is to save a clipboard item as file to a preset path using available tags as it's file name, and avoiding a dialogue for user input.

Since this doesn't take user input there are few defaults that you need to setup initially.  
After installing (importing the .ini file into File>Commands) open this script to edit these options:

` currentPath('C:/abc/xyz') `  
Set your default folder path. (widows user should use `/`)

` var words = 3 `  
Set number of words to use from tags (not number of tags)
	
`	var defaultname = 'clip' `  
Set default file name if there are no tags.

Shortcut: 'Ctrl + Alt + s' by default.

Credits: this script has been be inspired from https://github.com/hluk/copyq-commands/blob/master/Application/save-item-clipboard-to-file.ini


