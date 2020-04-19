# bash_profile
## Terminal: run source ~/.bash_profile every time start new terminal

1. Creating a .bash_profile on your mac
* You have to open that file with a text editor and then save it.

> touch ~/.bash_profile; open ~/.bash_profile

* You can use other editors:

> nano ~/.bash_profile
> mate ~/.bash_profile
> vim ~/.bash_profile

2. run source ~/.bash_profile every time start new terminal

> sudo nano ~/.zshrc

> if [ -f ~/.bash_profile ]; then
>  . ~/.bash_profile
> fi
