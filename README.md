# dotfiles

To use the installation directory:
1. `cd` to the dotfiles directory
2. Make the script executable `chmod +x *.sh`
3. `. ./install-essentials.sh`
4. `. ./install-extra.sh`

To stow the dotfiles: 
1. Install stow using `sudo apt install stow`.
2. `cd` to the dotfiles directory
3. Make the script executable `chmod +x stow-wsl.sh`
4. Run the bash script that stows the configurations `. ./stow-wsl.sh`
