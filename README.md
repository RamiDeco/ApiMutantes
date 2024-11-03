Guía de ejecución del proyecto:

    Descargar el repositorio en formato zip

    Configuración del entorno:
        Tener Java y Gradle instalados.
        Configurar las propiedades de la base de datos H2 en el archivo application.properties.

    Ejecución del proyecto de manera local:
        Una vez configurado el proyecto se ejecuta la aplicación main.

    Tests:
        Para ejecutar los tests y comprobar el code coverage, se ejecuta PersonaServiceTest

    Acceso a los servicios:
        Con un servicio cómo Postman puede interactuar con la API mientras se corre la aplicación usando la siguiente URL: http://localhost:8080 y acceder a los servicios posibles:
            Detección de mutantes: POST /mutant/
            Estadísticas: GET /stats
