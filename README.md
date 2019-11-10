# Proyecto Final Desarrolo Web Desafio Latam

## Nombre del proyecto:
Ion Water Page

## ¿Es un proyecto personal o para un tercero?
Proyecto para Terceros

## Descripción breve del proyecto:
## ¿Quiénes son los usuarios?
      los usuarios son: empresas y personas naturales
## ¿Cuál debería ser la conversión de éstos?
      interioriorizar al interes de la compra

<br />
### Sketch General:
***
![alt tag](https://lh3.googleusercontent.com/F2p1oi8xq73abhtJCTCSx_GUrvj8UwCVCYpKkjGrZe7Z1myCq7-ob47lt97__yC7BZ6-VS2omhMw-DumoFQ9rJrCQWTVIyNR_cBtFKIQio2Y150j49i7j_lHXQUsMZsC20LUqAoOii7Onwp3pOLtcpcqbqc-0ComC0KEMa_k10_myN6fLx4a48hjD4GUYasf8dWpRcfG8p2_jHd4GmnjPUrtSWqztoemwULML7b30OQ5p9gVkAd5XOzbX8iFlXPd5FHsir4qzQe61ICENa3Z3UgJhrrRvWom98oQpxoijJAK3qyJxAITVK7hsDBXdEDVla0AvOJleD5GrgjwqRGxdg8LIEQXJQEZbsM93G4Nhv7mCAf2iW1oAXVSIF7HSetXCnl969_Md9AU7ws6GM4XIqYscjjob-9mVWkyxAKV2az5FjFhqUUNVvQFJRJDPGmDW6QHpjUd4t5-fEhHb1aeOAfdXqo3ho2b0k8iJSWOix3C3E56Qd1pP3cpTdIRtW01IhBzHzbX1Evvk1_xTsmtOzt4Y1dKoxd-Zh66VztNpGa1Eh87HJkzhqJLe3RjXw3zX5POPhfxDjxjf9pYUrxqq8MLpkZ3FSieJamFUDygZ_xCHbpjwwY28ta2ZRA38_M9lIEA8DIyI5HRmaqOumt3T-26mMJUhY8ER1GNRy5nEHuCzPpXV2y5qg=w437-h470-no)
***

<br />

# Guia de Estilos:

## Colores Utilizados:
  -#fff (white)
  -#03A9F4
  -#2980B9
  -#def1f0
## Tipografias Utilizadas:
      -Roboto:
            ### Light, Regular
            
           
- Start: con el comando `npm run start` (o su atajo: `npm start`) iniciaremos el servidor y a su vez se abrirá el navegador por defecto para que podamos ir viendo los cambios que se vayan realizando. Es importante destacar que este comando quedará esperando cada cambio que se realice en los archivos, por ende deberá seguir ejecutándose indefinidamente. Si queremos detener su ejecución utilizaremos la combinación de teclas: `control + c` y para reiniciar volveremos a usar el comando `npm run start`.
- Build: el comando `npm run build` minifica tanto los archivos js como css, dejando todo listo para subir a producción.

<br />

***

Es necesario aclarar que los comandos `npm run start` y `npm run build` deben ser ejecutados en la consola dentro de la carpeta `_webpack`, al igual que el comando `npm install`.

***
<br />

#### Webpack DevServer
El puerto por defecto que se utilizará será el :8081, sin embargo dentro de las configuraciones podremos cambiarlo en el archivo `webpack.c.js`.
Una vez que se ejecute el comando `npm start` se abrirá el navegador por defeto del computador, sin embargo podríamos especificar qué navegador queremos que se abra; por ejemplo con la opción: `open: 'Google Chrome'` en las configuraciones del devServer, en el anteriormente mencionado archivo.

#### Carpetas para el Servidor 
En la carpeta raíz encontrarás otras dos que su nombre comienzan con `_`, las que serían: `_resources` y `_webpack`. Se han creado con ese nombre con el objetivo de recordar rápidamente cuales son las carpetas que no se deben subir al servidor. La primera porque contiene todos los archivos SASS que aunque quieras compartir el código fuente, el navegador igualmente no tendrá como mostrar ese contenido. La segunda es porque los archivos de configuración de Webpack son muy pesados y agregarías peso innecesario en el servidor.
