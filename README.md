# Installation
1. Clone this repository with `--recursive` parameter
   ```shell
   git clone git@github.com:Ekierka/dotfiles.git --recursive
   ```
2. [Install homebrew](https://brew.sh)
3. [Install Oh-my-zsh](https://ohmyz.sh)
4. Bind dotfiles
    ```shell
    bootstrap install
    ```
5. Install homebrew packages
   ```shell
   brew bundle install --file=~/.brewfile
   ```
6. Disable delay on dock show
   ```shell
   defaults write com.apple.Dock autohide-delay -float 0 && killall Dock
   ```
