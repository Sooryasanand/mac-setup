# Mac Setup
My personal mac setup

![My mac setup](https://github.com/Sooryasanand/mac-setup/blob/main/Screenshots/Screenshot%202023-08-30%20at%208.06.54%20pm.png?raw=true)

This repo contains info on all the apps / tools / settings I use on my Mac.

## Homebrew Setup

Homebrew allows us to install tools and apps from the command line.

To install it, open up the built in Terminal app and run this command:
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Autoinstall xcode

## Coding Setup

### Project Folder
Create a project folder in the '/username' folder to organise all my personal project

### Git
Git to access git files
```
brew install git
```

Configure git with your name and email:

```sh
git config --global user.name USERNAME

git config --global user.email EMAIL
```

### Terminal
Iterm2 to replace existing terminal
```
brew install iterm2
```
Once installed, launch it and customize the settings / preferences to your liking. These are my preferred settings:

### Oh My Zsh
To make the terminal look good
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Powerlevel10k
Install Powerlevel10k to customise the terminal
```
brew install romkatv/powerlevel10k/powerlevel10k
echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
source ~/.zshrc
```

### Oh My Zsh Plugin

#### Autosuggestions

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

    ```sh
    plugins=( 
        # other plugins...
        zsh-autosuggestions
    )
    ```

3. Start a new terminal session.

#### Syntx Highlighting

1. Clone this repository in oh-my-zsh's plugins directory:

    ```zsh
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```

2. Activate the plugin in `~/.zshrc`:

    ```zsh
    plugins=( [plugins...] zsh-syntax-highlighting)
    ```

3. Restart zsh (such as by opening a new instance of your terminal emulator).

### Visual Studio Code
Default coding editor
```
brew install --cask visual-studio-code
```
### Node
Node and npm setup
```
brew install node
```

## OS Productivity

### Brave
Brave is a free and open-source web browser developed by Brave Software, Inc. based on the Chromium web browser.
```
brew install brave-browser
```
### Alfred
An alternate to spotlight with more functionality
```
brew install alfred
```
### Window Managment
I use rectangle to move and resize windows using keyboard shortcuts. I used to use spectacle, but rectangle is more regularly maintained and allows me to use all of the same keyboard shortcuts as spectacle.
```
brew install rectangle
```
### App Switching
I use an app switcher called AltTab. It shows full window previews, and has an option to show a preview for every open window in all applications (even minimized ones).
```
brew install alt-tab
```
### Android File Transfer
App to transfer files to and from android phone
```
brew install android-file-transfer
```
### Discord
Chatting app to talk with friends
```
brew install discord
```
### Keka
Keka is a file archiver
```
brew install keka
```
### Notion
Notion is a freemium productivity and note-taking web application
```
brew install notion
```
### Bitwarden
Bitwarden is an open-source password mananger
```
brew install bitwarden
```
### Balena Etcher
balenaEtcher is a free and open-source utility used for writing image files such as .iso and .img files, as well as zipped folders onto storage media to create live SD cards and USB flash drives.
```
brew install balenaetcher
```
### Todoist
Todoist is a to-do list and task manager
```
brew install todoist
```
### Whatsapp
App Client for whatsapp to access whatsapp chat on desktop
[Install](https://www.whatsapp.com/download) Whatsapp here

## Creative Tools

### DaVinci Resolve
DaVinci Resolve is a color grading, color correction, visual effects, and audio post-production video editing application. 
Click [here](https://www.blackmagicdesign.com/au/products/davinciresolve/) to install Davinci Resolve
### Vlc
VLC media player to play any video file
```
brew install vlc
```
### Audacity
Audacity is a free and open-source digital audio editor and recording application software
```
brew install audacity
```
### Gimp
GIMP is a cross-platform image editor
```
brew install gimp
```
### Inkscape
Inkscape is professional quality vector graphics software
```
brew install inkscape
```

## OS Setting

### Background Images
Background image can be cloned from this repo. It's stored inside the "Background Images" folder

### Finder
* Finder -> Preferences
   * Uncheck Hard Disk
   * Change New Finder windows show -> Downloads
   * Check Open folders in tabs instead of new windows
 * Finder -> Sidebar
   * Check everything except home folder, 'Icloud folder', 'Shared' and 'Cloud Storage'
 * Finder -> Advanced
   * Tick Everything except for section under 'Keep folders on top:"
   * Select 'Search this mac'
  
### System Settings
  #### Battery Settings
  * Show Battery Percentage
    
  #### Desktop & Dock
  * Dock Size -> 1/4th Scale
  * Magnification -> 2/4th Scale
  * Minimise Windows Using -> Genie Effect
  * Tick minimise windows into application icon
  * Disable auto hide and show in the dock
  * Tick Animate open application
  * Tick show indicaters for open application
  * Auto hide and show menubar during full screen mode
  * Enable close windows when quitting an application
  * Set "Brave" as deafult browser
  
  #### Trackpad
  * Enable tap to click

## Brave Setup
* Bitwarden
* Sync Brave

## VScode Setup
### VScode Extensions
* Atom One Dark - Vscode Theme
* vscode icons - Icon pack for vscode
* Error Lens - Vscode highlights errors and warnings inline









