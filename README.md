# Practica-de-laboratorio-07-Gestion-de-Archivos-de-texto-en-Java
En esta practica se desarrollara un sistema en JAVA que me permita encriptar un archivo de texto. 

### Lenguaje

+ Java = JDK 1.8
+ IDE = NetBeans Apache 11.3

### Librerias

+ java.io.BufferedWriter;
+ java.io.File;
+ java.io.FileNotFoundException;
+ java.io.FileWriter;
+ java.io.IOException;
+ javax.swing.JFileChooser;
+ javax.swing.JOptionPane;

## Realizacion de la practica

+ Se creo un proyecto en java con el nombre de “Practica-07_VazquezAriel_AlvaradoAndres”.
En el cual se diseño una ventana con la siguiente interfaz gráfica:

![image](https://user-images.githubusercontent.com/64930023/87271205-2f8c0500-c498-11ea-89a7-12c6c10e7651.png)

+ Se programaron los siguientes metodos:

+ El metodo encriptar(String texto) convierte el string ingresado en un array de caracteres el cual lo recorre con un for y aumenta 3 numeros mas al char

+ El metodo guardarEnTexto(String ruta, String texto)  instancia un nuevo FileWriter al cual le pasa la rta ingreasa y se escribe el texto que se ingreso

+ El metodo seleccionarRuta() asemos uso de la clase JFileChooser para que el usuario escoja el directorio en el que quiere que se guarde el archivo

## Ejecucion del programa:

![image](https://user-images.githubusercontent.com/64930023/87272345-9101a300-c49b-11ea-91de-c0e0263e406a.png)

![image](https://user-images.githubusercontent.com/64930023/87272379-b0003500-c49b-11ea-970d-988507f315f9.png)

![image](https://user-images.githubusercontent.com/64930023/87272411-c9a17c80-c49b-11ea-92d5-f76a6641006e.png)

Se recomienda descargar la practica para ejecutar todas las acciones posibles
