# Dotfiles

This dotfile repository contains a several folders which include `homefiles`, `sys-installs`, and `vim-config`. In the `homefiles` folder, it has a `.bashrc` that allows alias for certain commands as shortcut and a `symboliclink` script for backing up your current `.bashrc` in your system and creating a symbolic link for the `.bashrc` in this homefiles folder. For `sys-installs` folder, it has a `AWSCLIINstaller` script which install AWS Command Line Interface in your system. For `vim-config folder`, it has a `.vimrc` which includes plugins and certain color scheme that can be change or added. There also a `vundleinstall` script that install vundle and copies that `.vimrc` into your home directory.


## How to Use

To install vundle along with preconfigure vim with plugins and a color scheme, can be found here:
- [Vim Config and Vundle Installar](vim-config/vundleinstall)
- [Vim Documentation](vim-config/README.md)
- [.vimrc file](vim-config/.vimrc)
    - For manual configuration


For installation of AWS Command Interface, you can check the documentation and script for installation here:
- [AWS CLI Installer](sys-installs/AWSCliInstaller)
- [AWS CLI Documentation](sys-installs/README.md)


For backing up your current `.bashrc` and creating a symbolic link to this repository `.bash`, you find it here:
- [Symbolic Link and Backing Up .bashrc](homefiles/symboliclink)
- [Docementation](homefiles/README.md)
- [.bashrc file](homefiles/.bashrc)
    - For manual configuration

## Improvements

In this repository, there are certains areas I could improve:
- Addings comments in your scripts, explaining what they do
- Fixing error output for color schems in `.vimrc` script

