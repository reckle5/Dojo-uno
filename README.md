# Dojo Numero Uno






## Integrantes
* Juan Pablo Bianchi
* Ramiro Mion
* Mateo Domian
* Enrico Montes
* Carolina Gonzalez Parra
## Consigna

Realizar el circuito en TinckerCad para simular el semáforo y desarrollar el codigo fuente para su funcionamiento correcto. siguiendo las siguientes especificaciones:

1- El semáforo tiene que tener 2 leds de cada color como minimo, en caso de que uno se
rompa, lo ideal serian 3.

2- Tiene que implementar los tiempos correctos como se detallan a continuación.

3- El verde dura 45 segundos.

4- El amarillo dura 5 segundos.

5- Rojo dura 30 segundos.

6- Tiene que tener señalización para personas no videntes como se detalla a
continuación.

7- Durante el verde: No sonar

8- Durante el amarillo: Tiene que sonar 1 vez cada 2 segundos en un tono suave.

9- Durante el rojo: Tiene que sonar 1 vez por segundo en un tono fuerte.

## Funcionalidad

* Definimos todos los Leds en uso, el sonador e inicializamos un contador que luego va a ser ultilizado para poner en uso la bocina. 
* Creamos las siguientes funciones:
- PRENDER, enciende la luz del led
- APAGAR, apaga la luz del led
- SEMAFORO, combina las dos funciones anteriores y con un contador e iterando con un for ponemos en uso la bocina para temporizar cuando tiene que sonar
* En la funcion LOOP ponemos en uso el codigo anterior para que el semaforo funcione correctamente. 

## Link al Proyecto
[https://www.tinkercad.com/things/j9VzPzovFgQ-daring-tumelo-turing/editel?sharecode=SgQtuX44ve-T3RQVhKRews8Sb0uD6_6_83XdjDpMo1U)
