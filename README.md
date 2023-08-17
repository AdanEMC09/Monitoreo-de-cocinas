

# Introducción

En la actualidad, la cocina universitaria no solo se trata de preparar alimentos deliciosos; también es un espacio de encuentro, aprendizaje y diversidad. La inclusión en este contexto es esencial para garantizar que todos 
los miembros de la comunidad , independientemente de sus necesidades o habilidades, puedan disfrutar de una experiencia culinaria enriquecedora.

En nuestra búsqueda por optimizar procesos y mejorar la eficiencia, nos encontramos con la oportunidad de aplicar estas innovaciones a la cocina universitaria. Imagina una cocina que se adapta automáticamente a las preferencias de los usuarios, mantiene un ambiente óptimo para la preparación de alimentos y gestiona eficientemente los recursos energéticos.

# Justificación
El proyecto de cocina universitaria inclusiva con sistema de monitoreo y control ambiental para IoT busca crear
un entorno de cocina en el campus universitario que promueva la inclusión y la sostenibilidad. 
La justificación se basa en varios aspectos:


1. *Inclusión:* El proyecto busca asegurar que la cocina universitaria sea accesible para todas las personas,
incluyendo aquellas con discapacidades o necesidades especiales. La implementación de tecnología IoT puede
permitir ajustes personalizados y facilitar la participación de todos en las actividades de cocina.

2. *Sostenibilidad ambiental:* La tecnología de monitoreo y control ambiental permitirá gestionar de manera
eficiente la temperatura y humedad del entorno. Esto es especialmente importante en un contexto universitario,
donde la conciencia sobre la sostenibilidad es cada vez más relevante.

3. *Eficiencia operativa:* La tecnología IoT permitiría la supervisión en tiempo real de las condiciones ambientales 
y operativas de la cocina, lo que facilitaría la detección temprana de problemas y la toma de decisiones informadas 
para mantener un funcionamiento óptimo.

En resumen:
El proyecto busca combinar la inclusión, la sostenibilidad y la tecnología IoT para crear una cocina universitaria 
moderna y eficiente, que no solo sirva a las necesidades actuales, sino que también inspire a las generaciones futuras.

# Objetivo general 


El objetivo es promover la inclusión y la sostenibilidad a través de la implementación de tecnologías innovadoras en el entorno culinario universitario.

  # Objetivos específicos



1. Diseñar y desarrollar un sistema IoT para monitoreo y control ambiental en la cocina universitaria, incorporando sensores de temperatura, humedad y gas, con enfoque en la inclusión.
 

2. Crear una interfaz de usuario accesible y adaptable que permita a personas con discapacidades interactuar efectivamente con el sistema de monitoreo y recibir notificaciones relevantes.
 

3. Implementar el sistema en la cocina universitaria, asegurando su instalación, calibración y funcionamiento, y brindando capacitación sobre su uso a personal y usuarios.
 

4. Fomentar un entorno universitario inclusivo y seguro al proveer una cocina equipada con tecnología IoT que facilite la participación de todas las personas, promoviendo la igualdad.
 

5. Evaluar el impacto del sistema en inclusión y seguridad, recolectando retroalimentación de usuarios y realizando pruebas de usabilidad para medir su efectividad.
 

6. Documentar todo el proceso en un informe detallado, sirviendo como guía para futuros proyectos y como recurso educativo sobre tecnologías inclusivas en entornos académicos.

# sensores a  ocupar 

## Sensor de temperatura DHT11

Los sensores de temperatura son componentes eléctricos y electrónicos que, en calidad de sensores, permiten medir la temperatura mediante una señal eléctrica determinada. Dicha señal puede enviarse directamente o mediante el cambio de la resistencia. También se denominan sensores de calor o termosensores. Un sensor de temperatura se usa, entre otras aplicaciones, para el control de circuitos. Los sensores de temperatura también se llaman sensores de calor, detectores de calor o sondas térmicas.

## Sensor de gas MQ-6  

Este  sensor MQ-6 sensor de gas es adecuado para detectar la presencia de Gas LP,compuesto principalmente por Propano y Butano y Gas Natural (Metano) en el aire. El sensor puede detectar concentraciones de gas entre 200 y 1000 ppm y es de utilidad para detección de fugas de gas en el hogar y en la industria. Su velocidad de respuesta es bastante buena, por lo que puede activar cualquier dispositivo de manera oportuna.

La presentación es en un módulo que puede conectarse a un microcontrolador y se incluye la electrónica básica para realizar la interfaz con el sensor.

Funcionamiento: El sensor MQ-6 opera utilizando un elemento sensor sensible a los gases. Cuando los gases inflamables interactúan con este elemento, cambia su resistencia eléctrica. El cambio en la resistencia se puede medir y utilizar para determinar la concentración del gas en el entorno.

Especificaciones técnicas:

-Sensibilidad ajustable.

-Rango de detección: 300 a 10,000 ppm de gas butano (C4H10).

-Voltaje de operación: 5V (puede variar según el modelo).

-Salida analógica: Varía con la concentración de gas.

-Salida digital: Suele tener un potenciómetro para ajustar el nivel de umbral de detección.

# ESP8266

El ESP8266 es un pequeño chip o módulo que proporciona conectividad WiFi a dispositivos electrónicos. Fue desarrollado originalmente por la compañía Espressif Systems y ha ganado una gran popularidad debido a su bajo costo, capacidad de procesamiento y funcionalidad WiFi integrada.

Especificaciones técnicas:

Microcontrolador: El ESP8266 incorpora un microcontrolador RISC de 32 bits con velocidad de hasta 80 MHz.

WiFi: Soporta conectividad WiFi 802.11 b/g/n.

GPIO: Tiene varios pines GPIO (Entrada/Salida de Propósito General) que permiten la interacción con sensores, actuadores y otros dispositivos electrónicos.

Memoria: Dispone de memoria Flash para el almacenamiento de programas y datos.

Comunicación: Puede comunicarse a través de interfaces UART, SPI y I2C.

# Materiales 

Se necesitaran los siguientes materiales para poder desarrollar este proeycto:
Necesitamos los siguientes materias:

1 PROTOBOAR

1  ESP8266 

1 SENSOR DHT11

1 SENSOR MQ-6

2 LEDS

2 RESISTENCIAS

1 BUZZER 

CABLES MACHO MACHO 

CABLES HEMBRA MACHO

CABLE USB

PHP

MYSQL

Arduino

# Necesitamos tener instalado  arduino 

# Posteriormente agregaremos este código para la configuracion de wifi y para que nos mida el control de gas ,temperatura .
  Aqui mismo en githut encontraras el código en que se llama :
  Código configuracion de wifi



