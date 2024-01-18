1)  the default location of the configuration nvim is /home/<your_name>/.config/nvim/lua/custom/ just transfer these files to this path
2)  the first time you log in, the installation of packages will begin, if you can't install clang during installation, then try installing unzip (sudo pacman -S unzip / sudo apt get-install unzip) on your computer first, it will help you unzip the packages you are installing
3)  if you want to check if everything is installed, you need to use the command in vim :MasonInstall
4)  after that, apply the command :TSInstall cpp
