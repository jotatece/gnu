# Instalación de las VirtualBox Guest Additions en Lubuntu 18.04 
## Jotatecé
1. Actualizamos el sistema operativo:
```
  sudo apt-get update
```
```
  sudo apt-get upgrade
```
### Cuidado con esta instrucción
```
  sudo apt-get dist-upgrade
```
2. Instalar el framework DKMS
```
  sudo apt-get install dkms
```
* Cerrar la consola de comandos

3. Montar la imagen de las Guest Additions:
* Acceder a la unidad de CD/DVD y abrirla en un terminal mediante la tecla F4 o desde el menú <<Herramientas>>

*Una vez ahí, teclear:
```
  sudo sh ./VBoxLinuxAdditions.run
```
4. Reiniciar el equipo
