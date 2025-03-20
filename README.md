# EJ1_ex2_ED-
Documentación Técnica.
En este archivo se incluirán las capturas de pantalla del proceso de documentación de un proyecto usando Javadoc, así como los problemas encontrados e implementaciones necesarias para ponerlo en marcha.

# Cómo usar Javadoc y donde se encuentra en el IDE-

En este caso se explicará en el IDE Eclipse.

1. Seleccionar proyecto.

   
![image](https://github.com/user-attachments/assets/141a6d6c-3fd1-4a33-848a-b02eda36f653)



2. Project -> Generate Javadoc

   
![image](https://github.com/user-attachments/assets/3cf46fba-41c5-41fa-a0b8-ffba29d52a81)



3. El último paso sería seleccionar el proyecto y la ruta donde queremos que se guarde la documentación. Es común dejar la ruta por defecto para encontar la documentación dentro del proyecto.
   
   ![image](https://github.com/user-attachments/assets/ac53b511-66e8-4d22-96fd-075b7b21e13d)


# Implementación y solución de errores-

1. Javadoc utiliza la API de java para poder entender los métodos, variables y funciones del lenguaje pero necesita de diferentes etiquetas para que pueda identificar que documentar y que no.

2. Al intentar documentar el proyecto nos encontraremos con el primer error.

   
![image](https://github.com/user-attachments/assets/991fd7fb-e421-4731-8a6a-7fba5c0c5b19)

Este error se debe a que la API no esta preparada para interpretar el carácter �. Por lo que el proceso se corta y no es capaz de documentar el código.



3. Al eliminar el carácter el error se ha solucionado pero hay 8 errores nuevos que solucionar. Estos errores la mayoría están asociados a problemas de con la importación de librerías, por ejemplo que no se encuentra el paquete.

![image](https://github.com/user-attachments/assets/f8352687-c963-4d89-b4e3-8fee3bd3c97d)

4. Una vez solucionados los errores podemos volver a intentar crear la documentación.
![image](https://github.com/user-attachments/assets/c63932f8-6710-4448-baba-3bf8d4993c9c)

5. Podemos ver que hay advertencias, esto no quiere decir que la documentación no se haya creado. Cada advertencia simboliza que hay una función en el programa que el programador ha etiquetado para mandarsela a la api Javadoc.
Ya la documentación se ha creado en la carpeta por defecto en index-files
![image](https://github.com/user-attachments/assets/36540a08-42b6-4252-b6c1-0fb3d3a24048)


Se puede ver como se ha creado pero no hay nada, eso es porque no hemos añadido etiquetas al código que queremos documentar.


![image](https://github.com/user-attachments/assets/64d3275f-2d8d-47fa-b04a-0e03abdaa5f2)


# Cómo y donde utilizar las etiquetas-

Las etiquetas se suelen usar en métodos para explicar lo que hace el método de manera simplificada.
La finalidad de un método es ofrecer una funcionalidad a otra clase.
Y puede o no devolver nada o devolver algo.
Además puede recibir parámetros o no recibirlos.


Para poder generar estas etiquetas se puede hacer escribiendolás manualmente sobre el método, o como pasa con los getters, setters, constructores,etc también se puede generar automáticamente pero basándose en el método, es decir al seleccionar algo no válido el comentario no se hará.

Con el atajo de teclado ALT + SHIFT + J después de haber seleccionado el método se generarán todos los comentarios posibles.


Ejemplos:

Está función recibe un parámetro y no devuelve nada, por lo que el comentario que se hará será el hecho de recibir un parámetro id.

![image](https://github.com/user-attachments/assets/f6ab41ed-1b2c-4216-9e15-ba2bb244965d)


En cambio si seleccionamos todos los métodos al mismo tiempo Eclipse solo comentará el primero.

![image](https://github.com/user-attachments/assets/3b2f90ec-7c82-462c-a32e-cf7eb73fbaf1)



Lo que hecho es ir seleccionado los métodos válidos uno a uno para generar todas las etiquetas posibles.

# Resultados



![image](https://github.com/user-attachments/assets/e9832c6f-42bc-4d35-bb19-322e6cf5b5b9)




# Aquí estas los métodos



![image](https://github.com/user-attachments/assets/6d210214-fefc-4238-b789-bb109366a1c5)




