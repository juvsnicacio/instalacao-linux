## Instalação Padrão linux :octocat:

> docker
  1. Pacotes de pré-requisitos
  ```sh
  $ sudo apt install apt-transport-https ca-certificates curl software-properties-common
  ```
  2. Chave GPG para o repositório oficial do Docker**
  ```sh
  $ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
  ```
  3. Repositório do Docker às fontes do APT:
  ```sh
  $ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
  ```
  4. Instalação do Docker:**
  ```sh
  $ sudo apt install docker-ce
  ```
  5. Permissão no docker:**
  ```sh
  $ sudo usermod -aG docker ${USER}
  $ su - ${USER}
  ```
> docker-compose
  1. Baixar a versão estável:
  ```sh
  $ sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o                 /usr/local/bin/docker-compose
  ```
  2. Aplicar as permissões necessárias:
  ```sh
  $ sudo chmod +x /usr/local/bin/docker-compose
  ```
  3. Ao ocorrer erro na instalação:
  ```sh
  $ sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
  ```
  4. verificar a instalação:
  ```sh
  $ docker-compose --version
  ```
> snapcraft
  ```sh
  $ sudo apt install snapd
  ```
 
> git
  ```sh
  $ sudo apt install git
  ```
