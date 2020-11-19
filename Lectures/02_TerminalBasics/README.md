# Lec 02: Terminal Basics

As I covered in the previous lecture, Terminal commands are somewhat useful in your developing process and even in your every day life. 

In this lecture alone, I'll cover the basics of Terminal. Nothing fancy here as I'd be talking about customization and some more useful commands. 


## Customize Your Terminal

### Step 1: Install iTerm2
*iTerm2* offers [robust features](https://iterm2.com/features.html). Of course, you can stick to the default Terminal App as you wish.

You can download iTerm2 by clicking [this link](https://iterm2.com/downloads/stable/latest) or alternatively, you can head to [its website](https://iterm2.com/index.html) for more information.

### Step 2: Install the recommended font

+ [MesloLGS NF Regular.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf)
+ [MesloLGS NF Bold.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold.ttf)
+ [MesloLGS NF Italic.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Italic.ttf)
+ [MesloLGS NF Bold Italic.ttf](https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold%20Italic.ttf)


After downloading all those four files, you'll have to make `MesloLGS NF` font available to all applications on your system.

On *iTerm2*, you can do the following:

> Open iTerm2 → Preferences → Profiles → Text and set Font to MesloLGS NF. 
>
> Alternatively, type p10k configure and answer Yes when asked whether to install Meslo Nerd Font.

On *Terminal*, you can do the following:

> Apple Terminal Open Terminal → Preferences → Profiles → Text, click Change under Font and select MesloLGS NF family.

### Step 3: Install Oh My Zsh

Type in 

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

If lots of stuffs are showing up in your Terminal, add `ZSH_DISABLE_COMPFIX=true` to the beginning of your `.zshrc` file.


### Step 4: Install Powerlevel10k

```sh
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

And then set `ZSH_THEME="powerlevel10k/powerlevel10k"` in `~/.zshrc`.

After that type `source ~/.zshrc`.

![](https://i.imgur.com/qkr1w9U.png)

### Step 5: Add Plugins
+ iTerm2-Color-Schemes: <https://github.com/mbadolato/iTerm2-Color-Schemes>
+ Cloning the Git repository: `git clone https://github.com/zsh-users/zsh-docker.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-docker` (this doesn't offer the features I want)
+ Auto Suggestions: `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
+ Syntax Highlighting: `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting`

![](https://i.imgur.com/ReqIaOP.png)


### Step 6: Final One! Enable Syntax Highlighting in Vi
You can use my preset if you want to. Here is [the source](https://github.com/icheft/dotfiles/blob/master/vim/.vimrc).

Just create a `.vimrc` file under your home directory by typing `touch .vimrc` and then copy and paste the content shown above. 