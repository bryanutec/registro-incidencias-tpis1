# registro-incidencias-tpis1

> Aplicación Android para el registro de incidencias.

## Herramientas utilizadas

- Android Studio
- Kotlin
- Jetpack Compose
- Git/GitHub

## Estado actual

Pantalla inicial de la aplicación la cual contiene dos campos de 
ingreso de texto, menú seleccionador de prioridad, botón para validar la información ingresada 
y muestra de funcionamiento de acelerómetro.


## Durante la primer semana de noviembre:

Se implementaron registros mediante Log.d para observar
el ciclo de vida de MainActivity:

- onCreate()
- onStart()
- onResume()
- onPause()
- onStop()
- onDestroy()
- onRestart()

Se utilizó la etiqueta TPIS1_LIFECYCLE para identificar
los mensajes en Logcat.

## Pruebas realizadas:

1. Apertura inicial:
   onCreate, onStart, onResume.

2. Presionar Home y regresar:
   onPause, onStop, onRestart, onStart, onResume.

3. Rotación de pantalla:
   onPause, onStop, onDestroy.

### Como abrir el proyecto

Ejecutar con Android Studio en un dispositivo virtual de tamaño medio con API 37.1.

## Autor

- Bryan Sorto: estudiante UTEC.