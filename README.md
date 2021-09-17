# HackRF - RTLSDR

En este apartado se presenta el código utilizado en el HardWare (HackRF y RTL-SDR) para obtener las coordenadas GPS en la terminal del sistema operativo Linux.

Para hacer uso de estos comandos se es necesario tener el archivo de texto previamente descargado, abrir la terminal desde la ubicación en la que se guardo, e ingresar el siguiente comando: gnss-sdr --config_file=./nombre_del_archivo.conf

El tiempo de ejecución para obtener las coordenadas de la ubicación actual dependerá en gran medida del sitio en el que se encuentre puesto que al estar en un lugar cerrado el ruido de los objetos e inclusive la cantidad de nubes que se presenta en el cielo atenuara la señal GPS hasta el punto de llegar a tener un tiempo completamente indefinido. 

