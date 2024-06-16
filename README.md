# TIOT_connection_guide
Guía de conexiones entre ignition nube, NX y robotstudio

# SCADA

## Diseño

## Conexión

Una vez configurados correctamente, tanto en Ignition nube como en Ignition local, los componentes de MQTT DISTRIBUTOR, MQTT ENGINE, MQTT TRANSMISSION, se continúa con la conexión de los respectivos tags con las funciones del SCADA en el diseño.

Para esto, en el Designer de Ignition nube, dirigrise a la carpeta MQTT Engine en el Tag Browser, luego desplegar la carpeta Edge Nodes y después desplegar la carpeta My MQTT Group. Allí se encontraran todas las carpetas con los tags que se envían a la nube desde los Ignition locales de cada una de las escenas.

![image](https://github.com/jsduenass/TIOT_connection_guide/assets/80609467/e36c0c67-3a7c-4f1f-927d-875897f0ae4c)
![image](https://github.com/jsduenass/TIOT_connection_guide/assets/80609467/4a900119-79c3-4c1c-8fe7-ffcbf90e3350)

Asimismo, en la carpeta Default del Designer de Ignition nube, desplegar la carpeta MQTT Tags. Allí se encuentran todas las carpetas con los tags creados desde el Ignition nube, los cuales son enviados a la nube para que los reciban los Ignition locales de cada una de las escenas.

![image](https://github.com/jsduenass/TIOT_connection_guide/assets/80609467/016151d1-7744-4151-bccd-5dc5abbcaf8d)


## Implementación

Una vez terminados el diseño y las conexiones del SCADA, éste se puede implementar. Para esto es necesario dirigirse a Tools y luego desde Launch Perspective seleccionar Launch Session, lo cual abrirá una pestaña en el navegador mostrando el SCADA listo para su puesta en marcha.

![image](https://github.com/jsduenass/TIOT_connection_guide/assets/80609467/f6b8e471-d5a8-4277-944d-63cc3f1943d4)
![image](https://github.com/jsduenass/TIOT_connection_guide/assets/80609467/06aa846e-cd87-427a-aa93-834c75041024)

