# Dotfiles
![Screen Shot 2022-09-12 at 22 06 09](https://user-images.githubusercontent.com/87126382/189735560-98678287-7f93-4ada-be43-5a15f7e26cee.jpg)

## Quick Notes
- The text editor i use is emacs, more spacifically emacs-plus. Which is a tweaked version of emacs for macOS; you can install it with <br>
```brew install emacs-plus --HEAD --no-titlebar``` The Emacs configuration i use is one i didn't actually create, you can find it [here](https://github.com/doomemacs/doomemacs)
- The prompt i use is powerlevel10k with some default configuration options, [here is the github page to get it](https://github.com/romkatv/powerlevel10k). 

## Installation
### Install dependencies
- Install yabai ```brew install koekeishiya/formulae/yabai```
- Install skhd ```brew install koekeishiya/formulae/skhd```
- Install alacritty ```brew install alacritty```
- Install sketchybar ```brew tap FelixKratz/formulae; brew install sketchybar```
- Install oh-my-zsh (to get the zsh prompt) using the instructions [here](https://ohmyz.sh/#install) (just run the command there)

### (Not necessary) Install apps i used in the screenshot
- Fetch program: neofetch ```brew install neofetch```
- Matrix rain: cmatrix ```brew install cmatrix```
- Ascii aquarium: asciiquarium ```brew install asciiquarium```
- System monitor: htop ```brew install htop```

### Clone this repository
Clone this repo with the following command. <br>
```git clone https://github.com/itaysharir/Dotfiles.git```

### Rename some files
- Rename zsh/zshrc to .zshrc (add a dot in the beginning of the filename)

### Move files
- move sketchybar to ~/.config/sketchybar <br>
- Move alacritty to ~/.config/alacritty <br>
- Move yabai to ~/.config/yabai <br>
- Move skhd to ~/.config/skhd <br>
- Move zsh/.zshrc to ~/.zshrc (renamed from zshrc to .zshrc)

## That's it.
- Feel free to customize my dotfiles to your liking and to submit issues.

## Credits
- Thanks for [distrotube on yt](https://www.youtube.com/channel/UCVls1GmFKf6WlTraIb_IaJg) for the bar design, i remade his bar from scratch. <br>
- Also thanks for [archcraft](https://archcraft.io/) developers for the alacritty config, i took it from there.
