# obsidian_vimmode_arabic
## this is a workaround to use vim mode in obsidian while using arabic keyboard layout. I tried to use all standard vim key bindings
1. First add the community plugin vimrc support https://github.com/esm7/obsidian-vimrc-support
2. Second: just put the .obsidian.vimrc to the root of your Vault directory
you may encounter odd behavior due to the slightly different arabic keyboard layouts , just go the the vimrc and modify what causes the problem.
----
If you have a better way to do this please let me know.

I know that there is a feature in the vimrc support plugin that lets you use a fixed keyboard layout in normal mode but it's experimental and didn't work for me :(. And as far as i know Code mirror (codemirror.net) doesn't support :set keymap=arabic that we usually do in vim 
