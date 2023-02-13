# Introducción a Git y GitHub
- Veremos los siguientes temas a lo largo del refuerzo
## Instalar Git y Registrarse en GitHub
- Instalación de Git: https://git-scm.com/downloads
- Registro en GitHub: https://github.com/signup?source=login
## Creación de repositorio 
- En el entorno de Git Hub crearemos un nuevo respositorio llamado "refuerzo_python_steam"
- El siguiente paso sera crear una carpeta con el mismo nombre desde la terminal con los comandos:
-  ````mkdir: ````: Crear una carpeta
- ````cd````: Acceder a una carpeta
- ````code .````: Abrir esa carpeta con VS code
## Conectar Git y GitHub
- Para esto existen 2 opciones: 
### Primer Repositorio:
- Si este es nuestro primer repositorio el procedimiento es sumamante sencillo, usaremos los siguientes comandos:
- ````git init````: Este comando inicializa git en nuestra computadora
- ````git add . ````: Esto es para guardar los cambios que hayamos hecho (ya sea crear archivos o modificarlos)
- ````git commit -m "mensaje"````: Este comando se usa para ponerle un mensaje 'clave' a los cambios que hayamos hecho en nuestro repositorio
- ````git remote add origin https://github.com/monte1003/ejemplo.git````: Este comando lo que hace es conectar nuestro git con nuestro respositorio, para esto pondremos el link de nuestro respositorio en GitHub
- ````git push -u origin main````: Este comandos 'empuja' los cambios que guardamos con un mensaje a nuestro respositorio en GitHub
- ````git config --global user.email johndoe@example.com````: Es probable que mientras realizaremos este proceso nos pida validación de nuestros datos

### Otros Repositorios:
- Si este no es nuestro primer repositorio el procedimiento es similar pero con unos ligeros canbios con respecto a crear nuestro primer respositorio
- ````git remote add origin https://github.com/monte1003/ejemplo.git````: Con este comando le decimos a git que queremos trabajar ahora desde ese repositorio
-  ````git add . ````: Esto es para guardar los cambios que hayamos hecho (ya sea crear archivos o modificarlos)
-  ````git commit -m "mensaje"````: Este comando se usa para ponerle un mensaje 'clave' a los cambios que hayamos hecho en nuestro repositorio.
-  ````git push -u origin main````: Este comandos 'empuja' los cambios que guardamos con un mensaje a nuestro respositorio en GitHub