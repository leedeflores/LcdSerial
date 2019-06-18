# LcdSerial
Manejo de pantalla LCD HD44780 o compatible a 8 bits mediante 4 líneas de comunicación
En este proyecto manejamos una pantalla de caracteres LCD a través de un registro de corrimiento de 8 bits, por lo que solo necesitamos las líneas de:
1.- clock para el registro de corrimiento,
2.- datos para el registro de corrimiento,
3.- Strobe para el registro de corrimiento,
4.- R/S para la pantalla LCD y 
5.- En para la pantalla LCD.

Para optimizar conexiones unimos las señales de Strobe del registro de corrimieno  y la señal de enable [En] de la pantalla LCD para solo manejat 4 hilos!

El ejemplo mostrados pone el mensaje 

			            Hello World!
			                     Saludos

En la carpeta PICs se utiliza el microcontrolador PIC 16F887, y pines de proposito general, por lo que puede facilmente trasladarse a otro microcontrolador

En la carpeta Arduino encontraras las librerias para urilizarse.

Mas detalles en las carpetas correspondientes.
