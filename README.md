# comandoslinux
Alguns comandos do Linux.

DISPLAY=:0.0  -> para acessos ssh

eject - abre
eject -t fecha

for((i=0; i<10; i++)) do eject & eject -t & done -> abrir e fechar drive, loop

xset -display :0.0 dpms force off -> desliga

xset -display :0.0 dpms force o -> liga

xrandr -o inverted -> inverte

xrandr -o normal -> volta

gsettings set org.gnome.desktop.background picture-uri file:///home/... -> Trocar plano de fundo

wget -> baixar img

eog -> exibir imagem
