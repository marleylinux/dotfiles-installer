# \\ dotfiles + installer //

This is my current dotfiles + install script to download, install and copy the correct files in the correct places

It's a good 'minimal' base from what I believe.

# Instructions.

# YOU MAY NEED TO sudo chmod 777 the app if it wont launch as ./

git clone https://github.com/marleylinux/dotfiles && cd dotfiles-installer

then gcc dotfilesinstaller.c -o DotfilesInstaller && ./DotfilesInstaller
(there is a precompiled version included)

We can also chain the commands together at once.

git clone https://github.com/marleylinux/dotfiles && cd dotfiles && gcc dotfilesinstaller.c -o DotfilesInstaller && ./DotfilesInstaller
