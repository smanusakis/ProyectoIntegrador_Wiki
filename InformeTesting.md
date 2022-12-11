## **DigitalHousing**
### Informe Final de Testing & QA
12/08/2022

- Introducción
- Casos de Prueba
- Pruebas de Regresión
- Testing Estático
- División de Funcionalidades
- Tecnologías Utilizadas
- Resultados
- Conclusión 

___



### **Introducción**
En este informe se detalla el proceso de testeo que se llevó a cabo en cada uno de los sprint en el desarrollo de la aplicación de “DHousing”. Se explicará en base a que se escribieron los casos de prueba, sus automatizaciones y las tecnologías utilizadas en el proceso
<br>

## **Casos de prueba**
Para cada sprint se escribieron casos de prueba basados en las funcionalidades requeridas en las historias de usuario provistas. Como primera tarea del sprint, se listaron todas las historias de usuario y se procedió a realizar distintos casos de prueba por cada una de ellas en el caso de que fueran necesarios.
<br>

## **Pruebas de regresión**
Se creo una suite de pruebas de regresión teniendo en cuenta la criticidad de las cuales se hicieron en el inicio de cada sprint para asegurar el correcto desarrollo de las nuevas funcionalidades. También se hizo una revisión de estas al final, donde se decide si algunos de los nuevos casos de prueba escritos durante el sprint debieran formar parte de las pruebas de regresión.

Las funcionalidades críticas en donde se aplicaron estas pruebas fueron las siguientes:
- Login de Usuarios
- Búsqueda de Producto
- Reserva de Producto


### **Testing Estático**
Se realizaron testeos estáticos con la totalidad del grupo de desarrollo, en donde revisamos la correcta escritura y comprensión de las historias de usuario y el material y tecnologías disponibles para el correcto desarrollo de estas.


### **Division de funcionalidades**
Los casos de pruebas se dividieron en funcionalidades para su correcta categorización, organización e implementación. Las siguientes son:

- **Estructura del sitio:** La correcta visualización del sitio, experiencia de usuario y que sea responsive
- **Productos:** Búsqueda, acceso y correcta visualización de los detalles de cada producto.
- **Usuarios:** Logueo de usuarios, creación de cuenta y administración y seguridad.
- **Reservas:** Acceso a la pantalla de reservas, correcta creación de una y visualización del historial.
- **Administración:** Tareas de administración como la creación o actualización de un producto. Seguridad
  
### **Tecnologias Utilizadas**
Para el proceso de testeo se utilizaron las siguientes tecnologías:
- **Postman:** Esta tecnología se utilizo principalmente para la creación de testeos automatizados de las funcionalidades de backend. Se creo una colección categorizada por las distintas clases desarrolladas y sus respectivos endpoints. Esta tecnología nos permitió acceder a testeos más rápidos y detallados tanto en la fase de desarrollo como en las pruebas de regresión.
- **Selenium:** Esta tecnología se utilizó para la automatización de la implementación de los casos de prueba manuales. Se simulo la experiencia de un usuario al interactuar con el sitio y utilizar las diferentes funcionalidades y, de esta manera, se facilita y automatiza la tarea del tester.
- **Qase:** Es un software de manejo de casos de prueba y suites que nos permitió tener un mejor manejo y organización al momento de escribirlos.


### **Resultados**
Casos de prueba /Automatizaciones



Durante el proceso de testeo se encontraron un total de 8 defectos. Los cuales fueron debidamente reportados al equipo de desarrollo y se aplicaron las correcciones correspondientes. Luego de aplicar los testeos una ultima vez, se llego a la totalidad de pruebas exitosas con lo cual se le dio fin al proceso.
Conclusión
El proceso de testeo que se aplico durante el desarrollo facilito la detección de manera temprana de defectos y fallas, lo cual ahorro mucho tiempo a los desarrolladores al momento de continuar con nuevas funcionalidades. La tecnología más utilizada, además de los testeos manuales, fue Postman. Este software nos permitió hacer testeos inmediatos durante el desarrollo tanto para Backend como así su integración con el Frontend.
Con todas las pruebas realizadas de manera exitosa, los defectos solucionados y sin la detección de ningún defecto nuevo, se da por finalizado el informe y alcanzado el exit criteria para lanzar la aplicación a producción.



