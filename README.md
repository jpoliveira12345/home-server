# home-server
Repository made to document what and how I created my personal home server

## Install directly
* Webmin
* Recalbox
* OliveTin
* Portainer

## Install contenerised
* Conteinerised don't starve server
* qBittorrent
* NextCloud
* Emby
* Pihole
* VPN (TBD)


## Features
* Conteinerised don't starve server
  * docker run -v ${HOME}/:/data -p 10999-11000:10999-11000/udp -p 12346-12347:12346-12347/udp -e "DST_SERVER_ARCH=amd64" --restart=always --name dont-starve-together -d jamesits/dst-server:latest
* Start and stop don't starve server
* Back up don't starve server
* Enable/disable GUI: Using OliveTin
