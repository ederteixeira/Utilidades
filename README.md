# Instalação do Python no Linux


1- Atualizar o sistema: 

	sudo apt-get update && sudo apt-get upgrade

2- Instalando as dependências no Debian, Ubuntu, Mint, etc...

	sudo apt-get install build-essential zlib1g-dev libjpeg-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev sqlite3 liblzma-dev curl libbz2-dev

Obs. Em alguns casos, pode ser que precise instalar o 'curl'.

	sudo apt-get install curl

3- Baixar o python no site:

	https://www.python.org/

Exemplo: 	

	https://www.python.org/ftp/python/3.9.6/Python-3.9.6.tar.xz

4- Descompactar o arquivo do Python baixado:

	tar -xvf Python-3.9.6.tar.xz

5- Entrar na pasta do python, abrir o terminal e executar:

	./configure --enable-optimizations --with-ensurepip=install

6- Compilar e instalar:

	make -j 2

	sudo make altinstall
	
7- Verificar instalação:

	python3.9 --version

	pip --version

8- Instalar pip ou atualizar:


	sudo apt-get install python-pip
	
	pip3 install --upgrade pip
	
