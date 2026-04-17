Paso 1: Preparación del Código
Crear el archivo: Creamos Hola.java dentro de una carpeta (en tu caso, terminó dentro de src/).

Escribir el código: Añadimos la estructura de clase y el System.out.println.

Paso 2: Inicializar el Repositorio
git init: Le dijiste a tu carpeta que ahora es un repositorio de Git.

git add .: Preparaste el código inicial.

git commit -m "Primer commit": Guardaste esa primera versión en tu computadora.

Paso 3: Experimentar con Ramas (Branches)
git checkout -b feature-saludo: Creaste un "universo paralelo" para cambiar el texto sin dañar el original.

Modificar y Guardar: Editaste el saludo en el código y lo guardaste.

git add src/Hola.java + git commit -m "Cambio de texto": Guardaste ese experimento en la rama.

Paso 4: Fusionar y Limpiar
git checkout main: Regresaste a la rama principal.

git merge feature-saludo: Uniste el experimento exitoso con tu código principal.

Configurar .gitignore: Creaste el archivo para que Git ignore los .class.

git rm -r --cached .: El comando de "limpieza profunda" para que Git finalmente dejara de seguir los archivos que no querías (como el .class).

Paso 5: Subir a la Nube (GitHub)
git remote add origin [URL]: Conectaste tu terminal con tu cuenta de GitHub.

git add . + git commit -m "Limpieza final": Aseguraste que todo estuviera listo.

git push origin main: Enviaste todo tu trabajo a internet.