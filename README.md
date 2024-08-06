# 4100901-Mid_Term_Exam

## No funcionales:
1. Se configuraron 2 botones: Giro Izquierda (B1 en el código), Giro Derecha (B2 en el código).
2. Se configuraron 2 luces: Luz Izquierda (LL en código), Luz Derecha (LR en el código).

#### Funcionales:

1. Se hicieron dos funciones para el funcionamiento del Led y sus respectivas configuraciones.
2. En el while se implementaron ifs para poder enviar los mensajes al UART.
3. Se envian mensajes de información por la consola cuando hayan eventos en el sistema.
4. Si un botón de giro se presiona 1 vez: la luz del lado correspondiente parpadea 3 veces.
5. Si un botón de giro se presiona 2 o mas veces durante 500ms: la luz del lado correspondiente parpadea indefinidamente.
6. Si un botón de giro se presiona y la luz del otro lado esta activa: se desactiva la luz del otro lado.
7. La frecuencia de parpadeo de las luces debe ser de 2Hz.
