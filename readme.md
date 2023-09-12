##### 1.1 – Crea un directorio llamado repo01 en local (desde tu máquina) e ejecuta el comando pertinente para que dicho directorio para que se transforme el repositorio en local ¿Cómo podemos identificar que el repositorio se ha inicializado?
- Sale el texto ``Initialized empty Git repository in <carpeta>``
##### 1.2 – Añade un documento llamado readme.md dentro del repositorio (recuerda que MD es la extensión de los ficheros Markdown) y documenta en su interior todos los pasos que vas realizando para crear un repositorio, etc. Puedes añadir fotos o lo que creas conveniente
##### 1.3 – Añade el fichero que acabamos de añadir al repositorio al staging area, visualiza el estado del repositorio (con git status) y haz un snapshot (commit) del fichero hacía nuestro repositorio local. ¿En que “file status lifecycle” se encuentra el fichero?
- Sale el estado ``On branch master``
##### 1.4 – Intenta subir los ficheros al repositorio remoto mediante al comando git push ¿Se te ocurre que está pasando? (si no lo sabes aún no te preocupes)
- Sale le siguiente error: ``fatal: No configured push destination.`` Esto pasa porque no hay ningún servidor configurado para hacer push (GitHub, GitLab...)
##### 1.5 – Ejecuta el comando git remote –v e investiga porque no nos aparece nada
- Porque no hay ninguna URL de destino
##### 1.6 – Crea un repositorio remoto llamado repo01, asócialo a tu repositorio local
##### 1.7 – Vuelve a ejecutar el comando git remote –v nuevamente y explica el porque ahora si que aparece
- Porque hemos vinculado este git con el git de nuestra PC
##### 1.8 – Sube los cambios que hemos subido al snapshot local (commit) hacía al repositorio remoto
##### 1.9 – Ves al repositorio remoto (en este caso GitHub) y comprueba que se haya realizado el commit correctamente y observa que pasa en el repositorio ¿Observas algo peculiar?
