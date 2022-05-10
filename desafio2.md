# Consigna "ANÁLISIS COMPLETO DE PERFORMANCE":

* Vamos a trabajar sobre la ruta '/info', en modo fork, agregando ó extrayendo un console.log de la información colectada antes de devolverla al cliente. Además desactivaremos el child_process de la ruta '/randoms'.
Para ambas condiciones (con o sin console.log) en la ruta '/info' OBTENER:
  - El perfilamiento del servidor, realizando el test con --prof de node.js. Analizar los resultados obtenidos luego de procesarlos con --prof-process.
    > ubicación: "./result-info.txt" y "./result-process-info.txt"
  - Utilizaremos como test de carga Artillery en línea de comandos, emulando 50 conexiones concurrentes con 20 request por cada una. Extraer un reporte con los resultados en archivo de texto.
    > ubicación: "./result-artillery.txt"
##

* Luego utilizaremos Autocannon en línea de comandos, emulando 100 conexiones concurrentes realizadas en un tiempo de 20 segundos. Extraer un reporte con los resultados (puede ser un print screen de la consola):
  <p align="center"><img src="https://firebasestorage.googleapis.com/v0/b/backend-clases.appspot.com/o/autocannon.PNG?alt=media&token=468b7d1a-e425-4c44-826f-e08503224803" alt="autocannon"/></p>
##

* El perfilamiento del servidor con el modo inspector de node.js --inspect. Revisar el tiempo de los procesos menos performantes sobre el archivo fuente de inspección.
