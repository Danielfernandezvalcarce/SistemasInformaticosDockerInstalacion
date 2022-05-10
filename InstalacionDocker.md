# INSTALACION DE DOCKER

Docker es un proyecto de código abierto que automatiza el despliegue de aplicaciones dentro de contenedores de software, proporcionando una capa adicional de abstracción y automatización de virtualización de aplicaciones en múltiples sistemas operativos.

<img src="https://i.gyazo.com/ebe08b75e8fd052aba35ff0dadec32c2.png">

## DESCARGA E INSTALACION

Para descargar docker nos vamos a su pagina oficial https://www.docker.com/ y nos descargamos docker para nuestro sistema operativo, una vez instalado nos registramos en https://hub.docker.com/ e iniciamos el programa en nuestra maquina.

Nos deberia salir una pantalla principal parecida a la siguiente: 

<img src="https://i.gyazo.com/7bea74df1a1a313dd437c5bb4f0e6633.png">

Podemos curiosear un poco es interesante saber que contenedores tenemos
<img src="https://i.gyazo.com/6ebe23c8b38894130dd28bac6fce0b19.png">

## INICIO EN TERMINAL

Una vez completada la instalación nos vamos a nuestro terminal CMD o Powershell e introducimos el comando ``` docker run -d -p 80:80 docker/getting-started ``` y nos saldrá algo parecido a la siguiente imagen

<img src="https://i.gyazo.com/c57fae3d6a4adbf53c008dd4e5103170.png">

En este momento sabremos que docker está listo para ser usado en nuestra maquina, pero aun asi hay que probarlo.

Escogemos un contenedor cualquiera de la pagina https://hub.docker.com/search?q= , para esta actividad escogeremos un contenedor sencillo llamado "hello world". 
<img src="https://i.gyazo.com/f4c48d9d0b63509ffe6d02f18b084c4c.png">
https://hub.docker.com/_/hello-world

## PUESTA EN FUNCIONAMIENTO DEL CONTENEDOR

Para eso simplemente tenemos que ir a nuestro terminal CMD o Powershell y con el docker iniciado introducimos el siguiente comando ``` docker run hello-world ``` y nos devolverá algo parecido a la siguiente imagen:

<img src="https://i.gyazo.com/7809b89e08ddea5a7d4f6e3df4b514a6.png">

Y con esto habremos finalizado la instalacion de docker en nuestro computador.