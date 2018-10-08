# Qué hacer tras instalar Ubuntu 18.04 LTS
## Jotatecé
1. Configurar el soporte de idiomas

2. Actualizar el sistema
```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade
```

3. Instalar códecs, complementos multimedia y webs
```
sudo apt-get install ubuntu-restricted-extras
```
4. Habilitar el botón de minimizado.
## En mi caso esto no fue necesario, pero si ves que no tienes dicho botón, simplemente, escribe_
```
gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'minimize'
```
5. Instalar Retoques de GNOME.
```
sudo apt-get install gnome-tweaks-tool
