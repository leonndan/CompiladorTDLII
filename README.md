# Compilador C++


#Titulo

Compilador en C++

#Introduccion

A contuniacion podra ver mi proyecto de la clase de Traductores de lenguaje II que consiste en la elaboracion de un compilador, pasando por todas las fases del mismo, las cuales son:
*Analizador Lexico
*Analizador Sintactico
*Analizador Semantico
*Generacion de codigo ASM

#Requisitos

Para poder probar el compilador debera de contar con los siguientes IDE:

*Codeblocks
*MASM32

#Objetivo

El programa lee el archivo "entrada.txt" y comenzara todas las fases del compilador, una vez que el programa no detecte ningun error lexico, sintactico ni semantico procedera a la creacion del archivo ASM donde vendra el codigo ensamblador. El archivo generado tendra de nombre "salida.asm".

Una vez generado el archivo, con ayuda del MASM32 debera de abrir el archivo asm y darle click en "Console Build All" una vez que el MASM32 no detecte ningun error procedera a crear el codigo objeto y el ejecutbale. 

*El programa no cuenta con un sleep o entrada de teclado, por lo que debera de agregar la siguiente linea de comando en el MASM32 para permitir ver el ejecutable y que no se cierre : "mov eax, sval(input("Enter any press to continue..."))"*

Cuando se generen los archivos, se procedera a ejecutar el archivo .exe y se debera de mostrar en consola lo que se escribio en el archivo entrada.txt;

#Demostracion

Procederemos a hacer una suma basica en el archivo de entrada.txt:
![image](https://user-images.githubusercontent.com/97914817/169629929-6861111e-0102-472e-a087-164c542fe4b5.png)

En consola se muestra el archivo asm generado:
![image](https://user-images.githubusercontent.com/97914817/169629963-f505d9f3-8eea-4576-9ff5-d4387d083817.png)

![image](https://user-images.githubusercontent.com/97914817/169629967-2814d4c9-03be-4bfd-bb1b-010590addff5.png)



