<!-- PROJETO PARA SERVIDOR DE MEDIA  -->

Alguns comandos itens para rodar caso esteja utilizando um Raspberry Pi com Pi OS

- Configuração de teclado
  Edite o arquivo /etc/default/keyboard para

        XKBMODEL="abnt2"
        XKBLAYOUT="br"
        XKBVARIANT=""
        XKBOPTIONS="lv3:alt_switch,compose:rctrl"

  Reinicie o sistema

- Para demais confirações o wizzard do Pi OS pode ser acessado
  raspi-config

RAID - NAO CONSWGUI FAZER FUNCIONA AINDA

Segue o link do tutorial que funciona para configurar RAID1
https://gist.github.com/leandrofilipe/f9636be272f97d414652ce1f21e6b1f4

- Git

Intalei o git para baixar este projeto e poder rodar o docker compose daqui
apt install git

- Docker

Case esteja usando o Pi OS 64b poderá seguir este tutorial para instalação
https://docs.docker.com/engine/install/debian/
