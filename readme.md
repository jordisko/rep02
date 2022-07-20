# ESTOS SON LOS PRINCIPALES COMANDOS DE GITHUB:  


| clear                                            | Limpiamos la consola de GitBash                                                                                       |
|--------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| pwd                                              | Imprime la ruta del directorio actual                                                                                 |
| ls                                               | Lista el contenido del directorio actual                                                                              |
| cd \<nombredirectorio>                            | Entramos al directorio <nombredirectorio>                                                                             |
| cd ..                                            | Retrocedemos de directorio                                                                                            |
| mkdir                                            | Creamos un directorio en la localización actual                                                                       |
| code .                                           | Abrimos el directorio en Visual Studio Code                                                                           |
| git config user.name                             | Nos muestra el username actual                                                                                        |
| git config --global user.name "nuestro username" | Escribimos por encima del username actual "nuestro username"                                                          |
| git config --global user.email "nuestro email"   | Escribimos por encima del useremail actual "nuestro email"                                                            |
| git init                                         | Creamos un repositorio en el directorio en el que nos encontramos. Haciendolo así nuestro Working Directory           |
| git status                                       | Nos muestra los tanto los archivos que tenemmos en el Working  Directory como los que ya hemos subido al Staging Area |
| git log                                          | Nos muestra los archivos que hemos subido ya a nuestro Repositorio Local                                              |
| git add <file>                                   | Subimos "file" al Staging Area                                                                                        |
| git add .                                        | Subimos todos los archivos que tenemos en el Working Directory al Staging Area                                        |
| git rm -- cached <file>                          | Bajamos un archivo "file" que tengamos subido al Staging Area                                                         |
| git commit -m "comentario"                       | Subimos al Repositorio Local los archivos que tengamos en el  Staging Area                                            |
| git remote -v                                    | Chequea si tenemos Repositorios Remotos existentes                                                                    |
| git remote add origin <link de GitHub>           | Asociamos el repositorio local con el Repositorio Remoto del "link de GitHub"                                         |
| git branch -M "main"                             | Cambiamos de nombre a la rama principal de "master" a "main"                                                          |
| git push -u origin "main"                        | Subimos los archivos que tenemos ya en nuestro Repositorio Local al Repositorio Remoto                                |
| git pull                                         | Cogemos los ficheros del Repositorio Remoto                                                                           |
| git clone <link de GitHub>                       | Creamos un Repositorio Local a partir de clonar el  Repositorio Remoto de "link de GitHub"                            |                         |