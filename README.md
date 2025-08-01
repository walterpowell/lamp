In Termux (must have apache2, mariadb and php-fpm installed):

1. mkdir $HOME/bin && echo "PATH=$HOME/bin:$PATH; export PATH" > $HOME/.bashrc && . ~/.bashrc
2. curl https://raw.githubusercontent.com/walterpowell/lamp/refs/heads/master/lamp -o $HOME/bin/lamp && chmod +x $HOME/bin/lamp

Examples:

lamp (all servers up)
lamp -d (all servers down)
lamp -ap (apache2 and php-fpm up)
lamp -ap -d (apache2 and php-fpm down)
