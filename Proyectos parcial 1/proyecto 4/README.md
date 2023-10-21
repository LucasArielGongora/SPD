#Primer parcial domiciliario

##Integrantes:
    Góngora Lucas Ariel
    Gónzalez Facundo

##Proyecto: contador, sensor de temperatura y fotoresistencia.

![Tinkercad](./img/imagen%20de%20proyecto.png)

#Descripción: 
    Este proyecto es un sistema multifuncional que integra varias características autónomas. Cada componente cumple una función específica:

    La fotocélula controla un LED en función de la intensidad de la luz ambiental, lo que aporta un sistema de iluminación automático.

    El sensor de temperatura regula la rotación de un motor, proporcionando control térmico.

    Los botones permiten contar de 1 a 99 en las pantallas de 7 segmentos.

    El interruptor enciende y apaga todas las funcionalidades, permitiendo un control general del sistema.

#Funciones:

Este proyecto está diseñado para controlar varias funciones deforma independiente.
La función principal del proyecto,
que se ejecuta en el bucle principal de Arduino, 
combina estas funciones y permite que el sistema
opere de manera coordinada.
int estadoBoton();: Esta función verifica el estado de losbotones y devuelve un valor que indica si se ha presionado unbotón.

    void mostrar(int decena); Controla las pantallas de 7 segmentos 
    para mostrar los dígitos en función del valor pasado como argumento.

    void prendeNumero(int numero); Maneja la multiplexación de los display de 7 segmentos
    para encender (unidad o decena) según el número pasado como argumento.

    void imprimirNumero(int numero); Muestra un número en las pantallas de 7 segmentos dividiéndolo en decenas y unidades.

    int estadoInterruptor();: Verifica el estado del interruptor y 
    devuelve un valor que indica si está encendido o apagado.

    float temperatura = 0;: Esta variable almacena la lectura del sensor de temperatura y se utiliza para monitorear la temperatura actual del entorno.

    bool sistemaEncendido = true;: Esta variable controla el estado general del sistema, permitiendo encender y apagar todas las funciones del proyecto.

#Proyecto 

 :globe_with_meridians: **Link al proyecto:**
    [Proyecto](https://www.tu-enlace-del-proyecto.com)

![](img/youtube.png) **Link al video del proceso:**
[Video del Proyecto](https://youtu.be/r5sUtMV_ho4)
