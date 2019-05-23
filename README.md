## Instalação Padrão linux :octocat:

> docker
1. pacotes de pré-requisitos
```sh
$ sudo apt install apt-transport-https ca-certificates curl software-properties-common
```
2. chave GPG para o repositório oficial do Docker
```sh
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```
3. repositório do Docker às fontes do APT:
```sh
$ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
```
4. instalação do Docker
```sh
$ sudo apt install docker-ce
```
5. Permissão no docker
```sh
$ sudo usermod -aG docker ${USER}
$ su - ${USER}
```
> docker-compose

> snap
```sh
$ sudo apt install snapd
```
> php
```sh
$ sudo apt install php
```
> apache2
```sh
$ sudo apt install apache2
```
> mysql
```sh
$ sudo apt install mysql-server
$ sudo mysql_secure_installation
```
