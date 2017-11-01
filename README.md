## Setting Indentation in VIM editor

We all use some kind of text editor for writing our codes. But during our lab test in most of the colleges including ours we have to use the virtual console on a linux system. Now if you have vi editor then sorry I can't help you. Your life is fucked. No one can help you, not even God, even if he/she wanted to. But if your lucky stars are shining and you have VIM editor installed on your system then I have some good news for you :). With a little edit in a file you can easily set up a user friendly and more clean coding environment for yourself. 

Here are the step by step instructions:

1.Once you enter the console make sure you are in the home directory.
2.Now type "vim .vimrc" (without qoutes).
3.This .vimrc may be a new file you create or an old file you will edit. What you have to do is enter the insert mode and then type in the following lines:

set tabstop=8

set smartindent

4.Now go to the command mode and save the file.
5.That's it you are good to go. Now when you enter vim editor you will notice a small but noticable change in your user experience.
6.There is a lot more cool stuff you can do by editing this file. You can even enable  mouse in your vim editor but sadly only while running vim in your terminal not the console. Just enter

set mouse=a

and you are done.


One of the best .vimrc settings I have used is by our own senior Anmol Jagetia sir.[Click here](https://github.com/anmoljagetia/dotfiles/blob/master/vim/vimrc) to check out his other cool stuff and his profile. 

Thanks for reading and I hope I could be of any help to you :)
