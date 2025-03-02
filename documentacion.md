1-git config --global user.name "Tu Nombre"  
  git config --global user.email "tuemail@example.com"  
    (Establece tu nombre y correo electrónico para que Git los use en los commits. Esto es importante para que Git sepa quién está haciendo los cambios en los proyectos.)

2-git config --list
    (Muestra la configuración de Git, incluyendo el nombre y correo que acabas de configurar.)

3-git init
    (Crea un nuevo repositorio Git en la carpeta donde ejecutas el comando. Esto convierte la carpeta en un proyecto Git para hacer seguimiento de cambios.)

4-echo Esto es un trabajo sobre GIT. AlexisGil > readme.md
    (Crea un archivo llamado readme.md y le agrega el texto "Esto es un trabajo sobre GIT. AlexisGil") .

5-git add readme.md
    (Indica a Git que quieres incluir readme.md en el próximo commit.)

6-git commit -m "Primer commit: Creación del README"
    (Guarda los cambios en Git con un mensaje explicativo "Primer commit: Creación del README". Ahora Git tiene un registro de este archivo y su contenido en este punto del tiempo.)