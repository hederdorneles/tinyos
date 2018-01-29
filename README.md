# tinyos

O tinyos é dividido em duas parte, as ferramentas para compilação e etc, 
e também os seus fontes, necessários para a geração das imagens do SO.

## Install

$ sudo apt install avrdude avr-libc gcc-avr avrdude binutils-avr  <br />

Obtendo do repositório do GitHub.

$ cd /opt <br />
$ git clone git://github.com/tinyos/tinyos-main.git <br />

# Instalando tools. <br />

$ cd tinyos-main/tools <br />
$ ./Bootstrap <br />
$ ./configure <br />
$ make <br />
$ make install <br />
