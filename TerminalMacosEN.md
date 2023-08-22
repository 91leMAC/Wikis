## Link to the Terminal on MacOS tutorial
https://www.craft.me/s/vBuq1VHmLhqv7d

## Craft code
```
# The terminal on macOS

# Introduction

> Maybe you manage your documents files and you doesn’t like to move your hand on your mouse to your keyboard over and over. In prehistoric age of the informatic and public computer, you haven’t any mouse, and this was a good way to write faster. But it’s huggly and not user friendly, today you will learn how to transform your huggly terminal to a fully beauty tool who give you better moments that the finder (yes it’s only available on macOS for technical reason).

For showing you a better tutorial I learn & help me with the Josean Martinez video [watch here](https://www.youtube.com/watch?v=CF1tMjvHDRA&t=185s)

# Using the right terminal

The default terminal on macos are a little boring, you can customise it but not to far compare to [iTerm2](https://iterm2.com/). Which is fully free and very usefull.

   + ## 🌐 Downloading iTerm2

      We are using a faster way, the first try is a little hard but you will see it will be more practicall. So we are using basicelly an « terminal-app » called [brew](https://docs.brew.sh/Installation) this app will allows you to install apply with just **one** command.

      + ### Install brew
         1. Open terminal
         2. launch this command

```java
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

         3. Verify brew is installed by launching this command

```java
brew --version
```

         if you have the version of brew like that you are a fancy terminal, otherwise you can make an issue [here](https://github.com/Homebrew/brew/issues).

![CleanShot 2023-08-21 at 17.34.25.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/701A926D-DA54-4FB6-8657-1C8026C2D86F/72EBDE65-1DE8-47E4-9EEE-9D39808E7EB3_2/pySCZiXfiE17GdGvAh04HsN1d8qaZAYsJlQCqJwYn30z/CleanShot%202023-08-21%20at%2017.34.25.png)

      + ### Download iTerm2
         + In your terminal launch that

```java
brew install --cask iterm2
```

![CleanShot 2023-08-21 at 17.32.49@2x.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/701A926D-DA54-4FB6-8657-1C8026C2D86F/5000EC92-34DE-4E36-B3FF-A9C8AED8DF7C_2/f6qoQm0nK8d73A6Dpt26LH6KzkjoHk1yXdcdLKG4G50z/CleanShot%202023-08-21%20at%2017.32.492x.png)

   + ## 🔧 Configure iTerm2

      We are installing right now few « terminal-app » and others fancy stuff.

      + ### Install Git
         + In iTerm2 run this command which will you install [git](https://git-scm.com/)

```java
brew install git
```

      + ### Install Oh My Zsh

         This is an « terminal-app » who give you access to plugins and others very cool stuff.

         1. Install Oh My Zsh

```java
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

         2. To verify the framework oh my zsh is installed restart iTerm2 and look that you have your username in each of your iTerm2 pages.

![CleanShot 2023-08-21 at 17.41.05.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/701A926D-DA54-4FB6-8657-1C8026C2D86F/AB99C184-03B6-4A3B-935D-5EB1B7CABF65_2/1zqObkK8dYSLZXxmbPyIonK0gqGzYG2fipL4Ws0FKjUz/CleanShot%202023-08-21%20at%2017.41.05.png)

            *the green icons are customisation, so you doesn't have that enable.*

   + ## 🖌️ Customise iTerm2

      > 💡 Now in my explainations iTerm2 will be Terminal.    **iTerm2 ⇒ terminal**

      For aving this beautifull icons style, we are using [PowerLevel10k](https://github.com/romkatv/powerlevel10k).

         ### Install powerlevel10k

```java
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

         ### Activate powerlevel10k

         We install but powerlevel isn’t active, so we are getting to the `.zshr` file, who allows you to activate this "terminal app" and other stuff.

            + #### Activate via the Terminal (faster but harder)

               The terminal is a « finder-like » but without GUI, in this case you must say him who you want to go and what files you want to change.

               1. **Go in your main folder.**  Run  `cd $home` in your terminal . If you sucess you will see the « ~ » right in your tab name.
               2. **Open the file.** Run `vim ~/.zshrc` (we use "vim" this is « terminal-app » who allows you to open files directly with it).
               3. **Modify the file.** I recommend you to copy/paste my own `.zshrc` file who you can find [here](https://github.com/91leMAC/Wikis/blob/main/.zshrc).

                  Locate the « ZSH_THEME = "robbyrussel" »  and change by `ZSH_THEME="powerlevel10k/powerlevel10k"`

               1. **Save & exit.**
               2. **Applied the changes.** With running in the terminal `source ~/.zshrc`
            + #### Activate via the Finder (slower but easier)
               1. **Activate hidden files.** Run this command in your terminal to see the hidden files les deux commandes en même temps :

```java
defaults write com.apple.finder AppleShowAllFiles YES
killall Finder
```

               2. **Go to the main folder.**  Hit this key to open the user folder : *shift* + *command* + *H*

![CleanShot 2023-08-21 at 18.18.14.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/701A926D-DA54-4FB6-8657-1C8026C2D86F/DAFE7804-463A-41D0-A3B3-86454D8B51A1_2/4TyKMJTUGmmNNv9NaNczETkiKWI0an3SGddzsHaOhlEz/CleanShot%202023-08-21%20at%2018.18.14.png)

               3. **Locate & open the file.**  .zshrc and open it

![Image.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/701A926D-DA54-4FB6-8657-1C8026C2D86F/73A7BD10-D6E3-48E4-9689-FBFEB9ECD8A3_2/W1vyQGyJi4Y0HfWiGM192JY5eDIFk8l9wyJsVI1c9bEz/Image.png)

               4. **Rewrite.** Change *ZSH_THEME = "robbyrussel"* by `ZSH_THEME="powerlevel10k/powerlevel10k"`
               5. **Applied the changes.** Go in your terminal and write `source ~/.zshrc`

         ### Follow the setup guide and choose the best customisation

         > 💡Download the font that Oh my zsh propose you.

      ## Add ::colors::

         + ### Download Coolnight theme

            Run in your terminal :

```java
curl https://raw.githubusercontent.com/josean-dev/dev-environment-files/main/coolnight.itermcolors --output ~/Downloads/coolnight.itermcolors
```

         ### Apply coolnight theme

         1. Open your iTerm2 settings with *commands* + ,
         2. Go to profiles > colors

![Image.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/701A926D-DA54-4FB6-8657-1C8026C2D86F/B85B8182-6A4D-4793-98CB-92FCA36AFE69_2/bFKyDHW0EAC81Qs2zH2pyMG4zBi8vSqclOgJ9d4FIhkz/Image.png)

         3. Import the downloader colors profile « coolnight » (in download folder)

![CleanShot 2023-08-22 at 12.06.28.png](https://res.craft.do/user/full/cf60cb5e-0deb-d5d4-1ab3-9b0453fad6ab/doc/701A926D-DA54-4FB6-8657-1C8026C2D86F/D396DF58-3CD2-4754-A708-92A87B077EB2_2/ubXzV1U44aPrLtx0MgNhXyWF9lakvxfI9flWkGJJ8gMz/CleanShot%202023-08-22%20at%2012.06.28.png)

         4. Select the profile color
   + ## 🏘️Install plugins

      For installing plugin you just install it with the terminal and then add it to the `.zshc` file

      1. ### Installing the plugins

      **Autosuggestion** - this plugin will propose you autosuggestions when you write in your terminal

```java
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

      **Zsh-syntax-highlighting** - this plugin will hightlighting your words when you write in the terminal.

```java
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

      **Websearch** - this plugin allows you to access to your browsing with launching a commend in your terminal.

         « normally this plugin is already install »

      **Vscode** - this plugin give you access to vscode and allows you to open a folder or a file in vscode from your terminal.

         Open vscode and press ⇧⌘P to access to your command palette and launch that :

```java
Shell Command: Install 'code' command in PATH
```

      2. ### Apply them in the .zshrc file

         Open your `.zshrc`

         Replace  the line 80 « plugins =(…); » by

```java
plugins=(git zsh-autosuggestions zsh-syntax-highlighting web-search vscode)
```

      1. ### Save the .zshrc file

         Launch in your terminal `source .zshrc`

```
