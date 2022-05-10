# C-Minus
Repositorio de proyecto de C-Minus para la materia de Lenguajes y automatas II

Empezaremos con las configuraciones necesarias:

- Tener el Javac, esto se debe poner el bin del jdk que tengas en las variables del sistema.
- Tener Javacc descargado y ponerlo en las variables del sistema su carpeta bin.

Para ejecutarlo necesitaremos crear los archivos necesarios con los siguientes comando:

```
javacc compilador.jj
```

```
javac *.java
```

Ya configurado todo lo necesario, ahora podemos compilar los txt con pedazos de código, estos txt se llaman codigo1.txt, codigo2.txt y codigo3.txt, para poder ejecutar los ejemplos necesitaremos ejecutar los siguientes comandos que son:

```
java compilador < codigo1.txt > salida1.txt
```

Este comando nos generará un archivo txt con el resultado de su ejecución, este proyecto encuentra y guarda el identificador variables, su tipo de dato ya sea int, float o real, también si este mismo es una función o variable como tal, su tamaño si llega a hacer una cadena y su posición ya sea una variable global o interna de la clase, estos datos se guardan en un hashtable.  Además, realiza sumas o restas dependiendo su resultado, e identifica errores de tipo de dato.
