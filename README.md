# dicas_linux

Coisas para colocar dentro do .zshrc:

# More git aliases
alias fe="git submodule foreach "

# Some Cargo aliases
alias cb='cargo build'
alias ct='cargo test'
alias cc='cargo check'
alias cr='cargo run'
alias cu='cargo update'
alias ccc='cargo clean && cargo update && cargo build'
alias ci='cargo clippy'
#alias gps="git push --set-upstream origin $(git branch | grep '\*' | cut -d' ' -f2)"


Dica para instalação da fonte Hack. Seguir o tutorial [How to Manually Install, Update, and Uninstall Fonts on Linux](https://medium.com/source-words/how-to-manually-install-update-and-uninstall-fonts-on-linux-a8d09a3853b0)

# Arch Linux Setup Commands (by Bruno):

## YAY

    cd ~ && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si && cd .. && rm -rf yay

## ZSH

    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
    ln -s ~/projects/backup/.zshrc

## Highlight

    cd ~/.oh-my-zsh/custom/plugins && git clone https://github.com/zdharma/fast-syntax-highlighting.git

## GPG

    gpg --import < priv-key.asc
    gpg --edit-key email@gmail.com
    trust
    5

## SSH

    ssh-keygen -b 4096 -C identificacao -o -a 500
    eval "$(ssh-agent -s)"

## Gnome extensions

    gnome-shell-extension-installer 8 118 120 413 648 750 1031 1125

8: Places Status Indicator
118: No Topleft Hot Corner
120: system-monitor
413: AppKeys
648: BitcoinMarkets
750: OpenWeather
1031: TopIcons Plus
1125: Github Notifications


Sugestões de instalação de apps (por Bruno):

openssh
wget
htop
xclip
whois
vim
gedit
meld
visual-studio-code-bin

google-chrome
firefox-developer-edition
terminator
slack-desktop
spotify
transmission-gtk

ripgrep
fd
exa
bat
fasd
pass
gimp
imagemagick
diff-so-fancy
zsh-pure-prompt-git
python-virtualenvwrapper
adobe-source-code-pro-fonts
ipython
python-pip
stow
dmenu
google-cloud-sdk
flameshot
shellcheck

gnome-tweak-tool
gnome-shell-extensions
gnome-shell-extension-installer

