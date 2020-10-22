# Instalação do AVA Moodle

## Passo 1

>Criar pasta no ***Servidor*** para o Moodle no diretorio /var/www/

>$ mkdir /var/www/Moodle

## Passo 2

>Baixar na sua ***Maquina*** o Moodle no site.

>https://download.moodle.org/releases/latest/

## Passo 3

>mover para os ***Servidor*** o arquivo baixado.

>$ scp moodle-3.9.2.tgz wellikson@ip_servidor:/tmp

## Passo 4

>Descompactar o arquivo.

>$ tar xf moodle-3.9.2.tgz

## Passo 5

>mover o arquivo extraido para o diretorio criado.

>$ mv moodle/* /var/www/Moodle/

## Passo 6

>abrir phpmyadmin

>http://ip_servidor/phpmyadmin

>criar banco de dados

![imagem criando banco de dandos]()

## Passo 8

>Abrir moodle no servidor Apache

>http://ip_servidor

![imagem servidor web]()

## Passo 9

>configurar Moodle

>1. Selecionar idioma.

![imagem servidor web]()

>2. configurar endereço web, selecionar diretorio de dados e do do Moodle.

![imagem servidor web]()

>3. Escolher driver do Banco de dados.

![imagem servidor web]()

>4. Fazer verificação de plugins

![imagem servidor web]()