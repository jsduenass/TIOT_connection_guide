# TIOT_connection_guide
Guía de conexiones entre ignition nube, NX y robotstudio

# SCADA

## Diseño

## Conexión

Una vez configurados correctamente, tanto en Ignition nube como en Ignition local, los componentes de MQTT DISTRIBUTOR, MQTT ENGINE, MQTT TRANSMISSION, se continúa con la conexión de los respectivos tags con las funciones del SCADA en el diseño.

Para esto, en el Designer de Ignition nube, dirigrise a la carpeta MQTT Engine en el Tag Browser, luego desplegar la carpeta Edge Nodes y después desplegar la carpeta My MQTT Group. Allí se encontraran todas las carpetas con los tags que se envían a la nube desde los Ignition locales de cada una de las escenas.

![image](https://github.com/jsduenass/TIOT_connection_guide/assets/80609467/e36c0c67-3a7c-4f1f-927d-875897f0ae4c)


## Implementación
