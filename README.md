# Tarea-investigacion-ESP-Micropython-y-Wokwi
En este repositorio se encontrará la solución de la tarea investigativa sobre ESp32 wroom, Micropython y wokwi
## ESP-32 WROOM:
  La esp 32 es un microcontrolador de bajo costo producido por Espressif Systems, el cual cuenta con conectividad por medio de Bluetooth y Wifi, las características de estas conexiones varían dependiendo de cada modelo, ya que hay diferentes variantes, con más o menos pines los cuales permiten desde control de sensores y actuadores hasta tareas un poco más complejas y exigentes como la modulación de voz.
  <img width="150" height="75" alt="image" src="<img width="260" height="280" alt="image" src="https://github.com/user-attachments/assets/88522a1a-872f-43a7-a04b-bd621be51bc6" align="left" />
  El núcleo de este micro es el ESP32-D0WDQ6 y además cuenta con la rom Microprocesador Xtensa dual-core 32-bit LX6 hasta 240 MHz y las siguientes memorias:
   * Memoria ROM 448 KB
   * Memoria SRAM 520 KB
   * Memoria SRAM en RTC 16KB
 Los rangos de voltaje usados por esta tarjeta van desde los 3.3v hasta los 5v, pero los GPIO solo trabajan a 3.3v, por ende, uno de los pasos más importantes al momento de trabajar con este componente es calcular y verificar cuanto voltaje y corriente va a consumir el sistema para determinar si la esp será capaz de alimentar el sistema o si se necesita una fuente adicional para evitar daños en el componente electrónico o un mal funcionamiento del sistema.
## Mictro-python:
 <img width="170" height="170" alt="image" src="https://github.com/user-attachments/assets/eac34932-703f-40f2-a704-cd0667d56230" align="right" />
Es una alternativa al lenguaje de programación original Python, que ofrece una arquitectura mucho más ligera, lo que permite una implementación más ágil y eficiente en componentes poco robustos como lo son los microcontroladores.
 Este lenguaje utiliza librerías de Python, y como se mencionó anteriormente, es una alternativa mucho más sencilla y liviana para poder implementarla en procesadores con poca memoria, como los microcontroladores ESP32, arduino, etc.

## Wokwi:
Es un simulador online que permite realizar proyectos relacionados con microcontroladores como esp32, Arduino, STM32 y muchos otros componentes electrónicos como lo son sensores, actuadores, pantallas, leds, etc.
Es una gran alternativa ya que nos evita descragar un software pesado o que demande un equipo con ciertos requisitos, aunque tiene un pequeño pronlema y es que cuando sus servidores de simulacion estan ocupados exige un plan de pago para poder simular en dicha situacion, pero ofrece la alternativa de descargar su extension en visual code lo que soluciona este problema y nos permite simular proyectos con estos micros, algo que es tedioso o imposible de hacer en otros softwares de simulación.



  
  







- Referencias:
  1. https://pasionelectronica.com/esp32-caracteristicas-y-pines/
  2. https://micropython.org/
