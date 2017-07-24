## Instalar o Atom

- Efeturar download de https://atom.io

$ dpkg -i atom-amd64.deb

## Instalar o git

$ sudo apt-get install git

## Configurando git

$ git config --global user.name "YOUR NAME"
$ git config --global user.email "YOUR EMAIL ADDRESS"

$ git config --global core.editor "atom --new-window --wait"
$ git config --global merge.tool vimdiff

##  Gerar chave ssh

$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

## Iniciar o ssh-agent

$ eval "$(ssh-agent -s)"

## Adicionar a chave privada ao ssh-agent

$ ssh-add ~/.ssh/id_rsa

## Copiar chave e informar no github

$ gedit .ssh/id_rsa.pub

- informar em https://github.com/settings/keys
