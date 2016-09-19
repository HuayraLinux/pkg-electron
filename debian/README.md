Electron para Huayra
====================

Electron es un framework para javascript similar a node-webkit.

Este paquete contiene los archivos originales binarios porque
el sistema de construcción es casi o peor de malo que el de node-webkit.
(Para hacer el build de i386 se tiene que hacer desde un host de 64bits)

En el branch pkg-source de github hay una versión decente para empaquetarlo
desde el fuente para 64bits, pero aun no funciona el de 32bits.

Por éste motivo, decidimos empaquetarlo temporalmente de ésta manera hasta
lograr tener un build dentro de pbuilder para ambas arquitecturas.

Si nos podés ayudar visita https://github.com/HuayraLinux/pkg-electron




