# SPRINT 8 COHORT10 JEISSONORTIZ
## Pruebas Automatizadas para comprobar la funcionalidad de la Aplicacion WEB Urban Routes
### Introducción
Este proyecto tiene como objetivo automatizar las pruebas de la aplicación web Urban Routes, utilizando Selenium y Python. Las pruebas cubren el proceso completo de solicitar un taxi, desde la configuración de la dirección hasta la confirmación de la solicitud.

### Objetivos
- Verificar la funcionalidad de las principales características de la aplicación Urban Routes.
- Asegurar la calidad y consistencia de la aplicación.
- Documentar los pasos de automatización para futuras referencias.
### Requisitos previos:
- Python: Asegúrate de tener Python instalado en tu sistema. Puedes descargarlo desde https://www.python.org/downloads/.
- Git: Necesitarás Git para clonar el repositorio. Descárgalo e instálalo desde https://git-scm.com/.
- Paycharm: usa el siguiente enlace para descargarlo: https://www.jetbrains.com/pycharm/download/?section=windows#section=windows
- Es necesario en el proyecto de pychram tener Instalado pytest y selenium. 
### Tecnologías y Herramientas
- Selenium: Para la automatización de navegadores web.
- Python: Lenguaje de programación principal.
- Pytest: Framework de pruebas unitarias.
- Page Object Model (POM): Para organizar los elementos de la página y las acciones del usuario.
- ChromeDriver: Controlador de Chrome para interactuar con el navegador.
### Estructura del Proyecto (archivos)
- data.py: Contiene los datos de prueba
- retrive_phonecode.py: Incluye la función auxiliar, Este código devuelve un número de confirmación de teléfono y lo devuelve como un string.
- ubanroute_page.py: archivo donde está definida la clase UrbanRoutesPage, con los localizadores de elementos web y los métodos que hacen posible la interacción con la aplicación web.
- test_urbanroute.py: archivo donde están las pruebas unitarias para las diferentes funcionalidades de la aplicación.
- .gitignore: Hay varios tipos de archivos que no se deben subir a los repositorios. Ya sea porque no es necesario o por seguridad. Incluyen archivos generados automáticamente, tales como los registros. Con éste archivo Git ignora los archivos innecesarios. 
### Pruebas Cubiertas
- Configuración de la dirección: Verifica la capacidad de establecer la dirección de origen y destino.
- Selección de tarifa: Comprueba la selección de la tarifa "Comfort".
- Ingreso de datos personales: Valida la entrada de número de teléfono y datos de la tarjeta de crédito.
- Comentarios al conductor: Permite agregar mensajes personalizados al conductor.
- Opciones adicionales: Verifica la funcionalidad de agregar mantas, pañuelos y helados.
- Solicitud de taxi: Confirma que el proceso de solicitud de taxi se completa correctamente.
- Información del conductor: Verifica que se muestre la información del conductor asignado.
### Consideraciones Importantes
- Mantenimiento: Las pruebas deben mantenerse actualizadas para reflejar los cambios en la aplicación.

