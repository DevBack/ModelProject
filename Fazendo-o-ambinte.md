# Configurar o ambiente
## Máquina virtual
O ambiente de desenvolvimento pode ser configurado seguindo os seguintes passos:
1. Instalar [vagrant](https://www.vagrantup.com/)
2. Instalar [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
3. Clonar o projeto
4. Utilizar o comando vagrant up no diretório
5. Executar o comando vagrant ssh no diretório
6. Ir para o diretório /vagrant/(cd /vagrant/)
7. Executar o comando mkvirtualenv -p /urs/local/bin/python3.5 sas
8. Executar o comando pip install -r requirements

## Linux
1. Executar o comando chmod 777 no arquivo install-apt.sh
2. Executar o comamando sudo ./install-apt.sh
3. Executar o comando mkvirtualenv -p /urs/local/bin/python3.5 sas
4. Executar o comando pip install -r requirements 