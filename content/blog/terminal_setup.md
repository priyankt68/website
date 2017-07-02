---
author: "Priyank Trivedi"
date: 2017-03-29
linktitle: Terminal Setup
title: Terminal Setup to Boost Productivity
highlight: true

---

Terminals are software developer's best friend to boost productivity. Even in today's age of super complex IDEs, having a highly productive terminal setup can vastly increase the pace at which you get your tasks done.

Here, I will cover my terminal setup which has vastly enhanced my productivity. 

## iTerm2

I recently ditched the default ```Terminal.app``` by OSX and replaced it with iTerm2 and I am definitely not going back.

## Zsh

[Z Shell or Zsh](http://zsh.sourceforge.net) is another shell implementation similar to Bourne Again Shell(BAsh) and also a scripting language. All features of BAsh are already integrated in Zsh.

### Ubuntu

    sudo apt-get install zsh

If you face issue installing on Ubuntu, follow [this](https://gist.github.com/tsabat/1498393/0af7b86c3ff6e771217a3f6ef84c1ebd2222db80) thread.

### MacOSX
    
    brew install zsh
    
If you wish to understand why Zsh is awesome, check this desk by Brendon - [Why Zsh is Cooler than Your Shell](http://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692)

Some useful links:

* [No, Really. Use Zsh.](http://fendrich.se/blog/2012/09/28/no/)
* [Zsh-loves](http://grml.org/zsh/zsh-lovers.html)
* [ZSH Tips by ZZapper](http://www.rayninfo.co.uk/tips/zshtips.html)


## Adding plugins to Zsh

[OhMyZsh](http://ohmyz.sh) - Get Oh My Zsh using the following command.

    sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"



## tmux

It is a program which runs in your terminal and let's you switch between several programs and do a lot more. More details about tmux are [here](https://tmux.github.io).

### Customising tmux
 tmux uses a file called tmux.conf to store it's configuration.

 Here's my ```tmux.conf```. 

```
set-option -g default-shell /bin/zsh

# Tmux uses a 'control key', let's set it to 'Ctrl-a'
# Reason: 'Ctrl-a' is easier to reach than 'Ctrl-b'

unbind C-b
set-option -g prefix C-a
bind-key C-a send-prefix

```

This is most basic customisation. You can do much more than this Read more [here](http://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/).


