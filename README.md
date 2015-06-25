# -DSA-Grupo-3--2015
INTEGRANTES:
-	Contreras, Lucas Mariano 	Legajo: 430/5

-	Jourdon, Julian		Legajo: 424/7

-	Bezzi, Gaston			Legajo: 16/7

Como instalar y poner en funcionamiento la aplicacion web

Se utilizó la distribución debían 7.8, se lo procedió a instalar en una máquina virtual.
Dicha máquina virtual se  conecta a la maquina real en modo "bridge". 

Luego se busca tener el conjunto de herramientas de LAMP.

Se instaló el apache server que va servir de servidor local a la máquina virtual del proyecto. 
Con el comando: apt get install apache

Luego se instaló mysql para poder tener una base de datos y efectuar consultas sobre la misma.
Con  el comando: apt get install mysql

Luego se instaló un intérprete de php para poder ejecutar el proyecto programado en ese lenguaje.
Con el comando: apt get install phpmyadmin

Se tuvo que configurar el apache para que permita hacer los logs correspondientes del proyecto, luego se configuro el Mysql los usuarios junto con su contraseña, que podrán tener acceso a la base de datos.

También se utilizó la herramienta de "sshfs" para poder tener un volumen montado compartido entre la máquina virtual y la real y poder incluir el proyecto ahí y hacer las modificaciones necesarias en el código del proyecto.


