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

![imagem criando banco de dandos](https://github.com/Wellikson/Instalacao-Moodle/blob/main/criarBanco.png)

## Passo 8

>Abrir moodle no servidor Apache

>http://ip_servidor

![imagem servidor web](https://github.com/Wellikson/Instalacao-Moodle/blob/main/servidor.png)

## Passo 9

>configurar Moodle

>1. Selecionar idioma.

![imagem seleção de idioma](https://github.com/Wellikson/Instalacao-Moodle/blob/main/linguagem.png)

>2. configurar endereço web, selecionar diretorio de dados e do do Moodle.

![imagem diretorios](https://github.com/Wellikson/Instalacao-Moodle/blob/main/diretorios.png)

>3. Escolher driver do Banco de dados.

![imagem driver do Banco de dados](https://github.com/Wellikson/Instalacao-Moodle/blob/main/driverbanco.png)

>4. Fazer verificação de plugins

![imagem verificação de plugins](https://github.com/Wellikson/Instalacao-Moodle/blob/main/plugins.png)

>5. Por ultimo fazer a configuração de acesso criando usuario , loguin e senha.

![imagem configuração de acesso](https://github.com/Wellikson/Instalacao-Moodle/blob/main/Screen%20Capture_select-area_20201022165351.png)