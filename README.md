# Beetrack prueba Técnica - React native:
Este test está pensado para evaluar los conocimientos del candidato en React Native.

## El Problema
Crear una app en React Native, para iOS y Android que cuente con las siguientes vistas:

### 1.- Vista principal, listado de usuarios:

![alt text](https://raw.githubusercontent.com/Beetrack/react-native-test/main/images/Home.png "App")

Se requiere crear una app, que contará con una vista principal que liste una cantidad de usuarios que se obtienen desde la siguiente API:

[Random user API](https://randomuser.me/api/?results=30)

Cada ítem de la lista debe mostrar la siguiente información del usuario:
* Nombre
* Apellido
* Dirección
* Imagen

### 2.- Vista Mapa:

![alt text](https://raw.githubusercontent.com/Beetrack/react-native-test/main/images/Map.png "App")

Al presionar sobre el ítem de la lista mencionada en el punto anterior, abrir una nueva vista donde se despliegue un mapa, en el cual se muestre dos marcadores:
* Posición actual del dispositivo
* Posición del usuario de la lista que se seleccionó (esta información es parte de la respuesta de la API)

### 3.- Vista Formulario:

![alt text](https://raw.githubusercontent.com/Beetrack/react-native-test/main/images/Form.png "App")

Crear un formulario donde se pueda ingresar las coordenadas para luego desplegar la vista mapa.

Para llegar a esta vista, se puede implementar un botón en cualquiera de las vistas anteriores.

## Consideraciones:
* El diseño de la app no será parte de la evaluación, pueden usar los estilos por default de los dispositivos o incluir alguna librería. Sí se evaluará el orden y estructuración del proyecto en general.
* Puede utilizar cualquier librería externa adicional si es necesario.

## Criterio de evaluación:
* La app debe estar desarrollada usando Redux como patrón de arquitectura
* Utilizar routing y navigation con React Navigation
* Testing con jest de los componentes principales
* Código limpio, orden, estructuración y arquitectura del proyecto en general
* Resolución de problemas y performance
* Control de errores al consumir la API

![alt text](https://raw.githubusercontent.com/Beetrack/react-native-test/main/images/App.png "App")



