# confscreen1440x900
# Linux basados en debian
Configuracion de pantalla 1440x900 con adaptador hdmi a vga
la resolucion por defecto es de 1440x900 a 60hrz 
y la resolucion necesaria es de 59.90hrz 
entonces procedemos aplicar los siguientes comandos
#
# xrandr --newmode "1440x900_59.97"  106.42  1440 1520 1672 1904  900 901 904 932
# xrandr --addmode HDMI-A-0 "1440x900_59.97"

luego agragan el shell nueva_resolucion.sh a la carpeta /etc/profile.d/nueva_resolucion.sh
 y listo!!!!

