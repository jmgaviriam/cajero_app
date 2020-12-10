# Cajero App
Este es el front-end del ejercicio del Cajero. Esta construido sobre la base de __Vue.js__, un framework bastante sencillo para esta labor. 


## Ajusta para Heroku
Este proyecto está diseñado para correr específicamente en Heroku. Para ello, es importante que usted ajuste en el componente `UserBalance.vue`, en el llamado a la REST API, debe ajustar el endpoint correspondiente a la consulta del saldo del usuario, basado en el nombre de la app de `Heroku`. En este caso, en el ejemplo de este repositorio, se tiene la función del autor luego del despliegue.


## Requerimientos
Recuerde que para la ejecución de `Vue.JS`, debe instalar los siguientes paquetes: 
```
npm install --save axios
npm install --save vue-router
npm install express
```

## Ejecución
Una vez haya hecho esto, puede probar en su máquina local para verificar que todo funciona bien. Para ello, debe ejecutar la siguiente instrucción estando en la carpeta raíz de este proyecto:
```
node server.js
```