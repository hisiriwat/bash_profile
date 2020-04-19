# bash_profile
## Terminal: run source ~/.bash_profile every time start new terminal.

1. Creating a .bash_profile on your mac.
* You have to open that file with a text editor and then save it.

> touch ~/.bash_profile; open ~/.bash_profile

* You can use other editors:

> nano ~/.bash_profile

> mate ~/.bash_profile

> vim ~/.bash_profile

2. Run source ~/.bash_profile every time start new terminal.

> sudo nano ~/.zshrc

* If you are using **oh-my-zsh**, the default one that will be loaded automatically is **~/.zshrc**. All you need to do is adding the following at the end of **~/.zshrc**.

> if [ -f ~/.bash_profile ]; then

>  . ~/.bash_profile

> fi
