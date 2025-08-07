# DesafiodeLibrosAlura
Consumo de api Gutendex, que contiene una gran cantidad de distintos textos, donde el usuario puede consultar y bajar los mejores libros, se obtiene gran serie de datos, utilizando técnicamente JSON, con el mapeo de entidades (ORM), para ello Hibernate hace la persistencia de datos (JPA), hacia PostgreSQL o Mysql como base de datos, en este proceso se hace el CRUD para operaciones normales sobre la DB, consultas de los mejores textos, por autor, por fecha u otro requerimiento.

<img width="500" height="500" alt="La magia del saber en los libros" src="https://github.com/user-attachments/assets/9d9f2d2b-cee9-4c6c-b61e-80071e189450" />

En esta aplicación los usuarios pueden consultar distintos tipos de libros, por tema, autor, año de publicación, resumen analítico, materias consultadas.

https://github.com/user-attachments/assets/5bd3a6d4-1398-458f-bfcc-2010a2e24bff
Entonces, podemos describir la técnica que se ha estado aplicando en esta parte del curso, que ha sido de grana ayuda para consolidar los conocimientos,con los cuales elaborar la aplicación:

<img width="734" height="438" alt="mapeo de datos" src="https://github.com/user-attachments/assets/f874c925-74ef-4634-84d4-b4d54120fb19" />

Como describe la figura , tenemos el modelo de datos en PostgreSQL, el cual mantiene los objetos de datos de las clases de java, donde se puede apreciar el complemento de Hibernate, al considerar los objetos como entes relacionales, entre el requerimiento sobre una tabla en especial y el contenido específico por cada línea de la misma tabla, lo cual entrega mayor confiabilidad y estabilidad en la información.

<img width="835" height="535" alt="mapping de JPA" src="https://github.com/user-attachments/assets/51f409db-a62e-4b8f-b22d-e242669c1d9e" />

La persistencia de datos en java (JPA), aprovechando de utilizar el modelo del frameworks de Spring Boot y la base de datos POstGreSQL.

![el crud](https://github.com/user-attachments/assets/940c9667-e87f-454e-a197-5afbd86e1c2d)

Para las operaciones normales, se utiliza el CRUD, que permite hacer registros, lectura de datos, borrarlo o actualizar los mismos.

![Hibernate](https://github.com/user-attachments/assets/c97a933f-f4a3-4edd-824c-f8da9bcaca46)

Y finalmente podemos observar un menú para seleccionar libros y así consumir la API Gutendex:



![Menu Principal](https://github.com/user-attachments/assets/9f4b970c-2f7c-4579-a39d-377d075c915d)



