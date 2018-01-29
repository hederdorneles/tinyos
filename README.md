# tinyos

O tinyos é dividido em duas parte, as ferramentas para compilação e etc, 
e também os seus fontes, necessários para a geração das imagens do SO.

## Install

$ sudo apt install avrdude avr-libc gcc-avr avrdude binutils-avr 

Obtendo do repositório do GitHub.

$ cd /opt
$ git clone git://github.com/tinyos/tinyos-main.git

# Instalando tools.

$ cd tinyos-main/tools
$ ./Bootstrap
$ ./configure
$ make
$ make install
