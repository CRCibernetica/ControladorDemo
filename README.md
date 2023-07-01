# Notas del Proyecto
Un proyecto simple para repasar las ideas basicas del Ideaboard y IoT
Utilizar los datos de un sensor fotoresistencia para controlar un servomotor
Monitorear los datos, crear controles manuales y automaticos
## Entradas
* Sensor fotoresistencia (analogico) board.IO34
* GND, Vcc, AO --> board.IO34
## Salidas
* Servomotor --> board.IO4
## Monitoreo/HMI (Adafruit IO o Node-RED)
Empezamos con Adafruit IO y luego una version de Node-Red
## Topicos de MQTT
* topico de control: proyecto/xxxxx/comandos
* topico de datos: proyecto/xxxxx/datos/luz
## TODO
* [x] Probar conexiones fisicas
* [ ] Crear el codigo base (usando el ejemplo de Adafruit IO)
* [ ] Graficar los datos de luz en Adafruit IO
* [ ] Controlar el servo desde Adafruit IO
* [ ] Agregar logica de control