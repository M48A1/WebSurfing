## Base
###  install git
* apt install git -y

###  install ufw
* sudo apt install ufw

### install sudo 
* apt-get install sudo


## cert
* git clone https://github.com/slobys/acme.git /tmp/acme && mv /tmp/acme/* /root
* bash acme_2.0.sh

## Hysteria
* bash <(curl -fsSL https://raw.githubusercontent.com/jonssonyan/h-ui/main/install.sh)
