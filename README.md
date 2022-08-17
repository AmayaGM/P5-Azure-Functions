# Practica 4 con "Azure Functions"

*Crear un Azure Functions*

**Paso 1 _Functions_**
- Poner en la barra de busqueda "funciones" y elegir la opcion 
![Paso 1](/imagenes/img1.png)

**Paso 2 _Crear App Services_**
- Primero debemos elegir el boton "Crear" 
![Paso 2](/imagenes/img2.png)

- Ir a datos basicos
  ![Paso 2.1](/imagenes/img2_1.png)

  - Debemos elegir en detalles del proyecto:
      - La suscripcion
      - El grupo de recursos previamente creado
      ![Paso 2.1.1](/imagenes/img2_1_1.png)

  - Debemos elegir en detalles de instancia:
      - Nombre con el que queremos llamar la aplicacion
      - Elegir si queremos codigo o contenedor docker 
      - El entorno de ejecucion, en este caso Node.js
      - El sistema operativo
      - La region donde deseamos crearla
      ![Paso 2.1.2](/imagenes/img2_1_2.png)

  - Debemos elegir el sistema operativo y el plan
      ![Paso 2.1.3](/imagenes/img2_1_3.png)

- Dar en revisar y crear
  ![Paso 2.2](/imagenes/img2_1_4.png)

- Dar en crear
  ![Paso 2.3](/imagenes/img2_1_5.png)
      
**Paso 3 Abrir el recurso**
- Ir al recurso
![Paso 3](/imagenes/img3.png)

- Ir a funciones
  ![Paso 3.1](/imagenes/img3_1.png)

- Damos en crear
  ![Paso 3.2](/imagenes/img3_2.png)

- Posteriormente elegimos el entorno de desarrollo, el HTTP trigger y finalmente damos en "crear"
    ![Paso 3.3](/imagenes/img3_3.png) 

    - Ahora iremos a "codigo y prueba"
    ![Paso 3.3.1](imagenes/img3_3_1.png)

    - Programamos el codigo y lo probamos
    ![Paso 3.3.2](imagenes/img3_3_2.png)

    - Insertamos el dato necesario y ejecutamos
    ![Paso 3.3.3](imagenes/img3_3_3.png)

    - Finalmente se nos mostrara la corrida exitosa de nuestra programacion
    ![Paso 3.3.4](imagenes/img3_3_4.png)

    - A continuacion podremos obtener URL y copiar el link para poder utilizarlo en el proyecto que deseemos
    ![Paso 3.3.5](imagenes/img3_3_5.png)


