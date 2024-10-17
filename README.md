# Documentación del API de Inteligencia Artificial de GorqCloud
## Introducción
Esta documentación describe cómo utilizar y probar el API de Inteligencia Artificial de GorqCloud mediante Postman. GorqCloud es una potente plataforma de inteligencia artificial que ofrece una amplia gama de servicios, incluyendo procesamiento de lenguaje natural, análisis de datos y aprendizaje automático. Este API proporciona una interfaz para interactuar con los algoritmos de IA de GorqCloud, facilitando la integración de funcionalidades avanzadas en tus aplicaciones.

El propósito de este documento es guiarte a través del proceso de configuración y uso del API en Postman, una herramienta popular para realizar pruebas de API. Aquí aprenderás a realizar solicitudes HTTP, gestionar los endpoints disponibles y entender las respuestas que devuelve la API.

## Configuración Previa
Antes de comenzar a realizar pruebas con el API de GorqCloud, asegúrate de cumplir con los siguientes requisitos:

## Inicio 
 * Para empezar, primero debes ingresar a la página de GorqCloud y crear una cuenta. Puedes hacerlo desde [Aqui](https://console.groq.com/login)
   
![image](https://github.com/user-attachments/assets/3ac24ece-1734-46c8-b0ec-a545ff356714)
Una vez que hayas creado tu cuenta, dirígete a la sección de Documentación de GorqCloud, donde podrás encontrar toda la información referente al uso del API que nos interesa.

![image](https://github.com/user-attachments/assets/e8f80be5-7b2c-465a-b31b-912452330d17)
GorqCloud ofrece diferentes opciones, como Chat, Audio y Models. En este caso, nos enfocaremos en la funcionalidad de Chat.

![image](https://github.com/user-attachments/assets/395b9ae9-8c5b-4b16-a746-e25072fde58a)

Para poder usar el API, necesitarás una clave de uso personal. Esta se puede generar en la parte inferior de la documentación, donde GorqCloud te ofrece la opción de crear una nueva clave.

![image](https://github.com/user-attachments/assets/dc4879d6-6ca2-42e5-8aa8-31efc9fc60b7)

Al crear una clave, podrás darle un nombre para identificarla fácilmente.

![image](https://github.com/user-attachments/assets/e8c6dc0d-ffae-4cc9-8ce4-d6de1cfdd779)

Una vez creada, se te proporcionará una clave única. Guarda esta clave ya que la necesitarás para configurarla en Postman.

![image](https://github.com/user-attachments/assets/881edf51-29ab-4895-839c-ec01d0ca432d)

## Realización de Reactivo y Dependencia.
- Reactivo para el la base de datos:

  ![image](https://github.com/user-attachments/assets/da445b60-e45e-4e56-9343-88e70f1164ec)

-Dependencia Ingresada:

![image](https://github.com/user-attachments/assets/00de60a1-7121-4467-8c8c-2b25261bc6a6)


## Creación de la base de datos con MongoDB Atlas.
Con MongoDB Atlas hemos pasado nuestra base d datos local a nube, usando la url que nos da ingresandole en nuestro microservicio.

- Usamos el Cluster , seleccionando MO Sandbox que sera gratuito.

![image](https://github.com/user-attachments/assets/14703ac5-2db5-4c44-a27e-9fa3c1fc2768)

- Luego de darle connect a nuestro Clusters podremos elegir Drivers que nos otorgara la cadena de conexión.

![image](https://github.com/user-attachments/assets/0c15ce79-7002-4dd9-8c6d-616ce20707ed)

- Realizaremos la prueba en local usando MongoDB Compass:

![image](https://github.com/user-attachments/assets/a3c0d5ab-b4be-456e-871c-273d44c6934a)

- Visualizaremos la conexión ejecutandose correctamente:

![image](https://github.com/user-attachments/assets/3d183047-67e4-47be-b1f6-fb13ef956444)

- Lo ingresamos dentro de nuestro "application.properties", dandole el cadena de conexión:

![image](https://github.com/user-attachments/assets/46e5549b-aa73-44df-ba4a-4c97bc586c93)

Haci es como hemos pasado nuestro microservicio usando una base de datos local y Reactivo apra la bd.

![Snake animation](https://github.com/ElserManuel/ElserManuel/blob/output/github-contribution-grid-snake-dark.svg)
