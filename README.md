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



3. Al eliminar el carácter el error se ha solucionado pero hay 8 errores nuevos que solucionar. Estos errores la mayoría están asociados a problemas de librerías que han cambiado el nombre...

![image](https://github.com/user-attachments/assets/f8352687-c963-4d89-b4e3-8fee3bd3c97d)


4.



