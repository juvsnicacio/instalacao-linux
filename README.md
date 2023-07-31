## Instalação linux Padrão

> SNAP
- linux mint pre-instalation 
  ```sh
   sudo rm /etc/apt/preferences.d/nosnap.pref
  ```
- install snap 
  ```sh
   sudo apt install snapd
  ```
- download de apps na [snapcraft store](https://snapcraft.io/store)
> git
  ```sh
   sudo apt install git
   git config --global user.name "Juvanderson Nicacio"
   git config --global user.email juvandersonns@gmail.com
  ```
> apps
  ```sh
   sudo snap install docker &&
   sudo snap install intellij-idea-community --classic &&
   sudo snap install insomnia &&
   sudo snap install code --classic
  ```
> Permissão no docker:**
  ```sh
   sudo groupadd docker
   sudo usermod -aG docker $USER
  ```
