###### Asignatura de Desarrollo de aplicaciones web entorno del cliente
##### Unidad 0 - Herramientas de programación.
## Ejercicio de creación de repositorios

### 1 Exercici creació de repositoris

- Crear un repositorio nuevo con el nombre libro y mostrar su contenido.

- Configurar Git definiendo el nombre del usuario, el correo electrónico y activar el coloreado de la salida. Mostrar la configuración final.
![](assets/1.png)
![](assets/2.png)
![](assets/3.png)
![](assets/4.png)
- Comprobar el estado del repositorio. Crear un fichero indice.txt con el siguiente contenido:
```
Capítulo 1: Introducción a Git
Capítulo 2: Flujo de trabajo básico
Capítulo 3: Repositorios remotos
```
![](assets/5.png)
- Comprobar de nuevo el estado del repositorio. Añadir el fichero a la zona de intercambio temporal. Volver a comprobar una vez más el estado del repositorio.
![](assets/6.png)
![](assets/7.png)
- Realizar un commit de los últimos cambios con el mensaje “Añadido índice del libro.” y ver el estado del repositorio.
![](assets/8.png)
- Cambiar el fichero indice.txt. Mostrar los cambios con respecto a la última versión guardada en el repositorio. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3 sobre gestión de ramas”.
![](assets/9.png)
- Mostrar los cambios de la última versión del repositorio con respecto a la anterior. Cambiar el mensaje del último commit por “Añadido capítulo 3 sobre gestión de ramas al índice.” Volver a mostrar los últimos cambios del repositorio.
![](assets/10.png)

### 2 Exercici gestió de canvis

Clona el següent repositori per a fer l’exercici. https://github.com/asalber/libro-git

![](assets/e2/1.png)

> Este pas me l'he botat perquè d'aquesta manera l'exercici ja estava fet.

- Mostrar el historial de cambios del repositorio. 
![](assets/e2/2.png)


- Crear la carpeta capitulos y crear dentro de ella el fichero capitulo1.txt con algún texto. 
![](assets/e2/3.png)

Añadir los cambios a la zona de intercambio temporal. Hacer un commit de los cambios con el mensaje “Añadido capítulo 1.” Volver a mostrar el historial de cambios del repositorio.
![](assets/e2/4.png)


- Crear el fichero capitulo2.txt en la carpeta capitulos con algún texto. Añadir los cambios a la zona de intercambio temporal. Hacer un commit de los cambios con el mensaje “Añadido capítulo 3.” 
![](assets/e2/5.png)

- Mostrar las diferencias entre la primera y la última versión del repositorio.
![](assets/e2/6.png)

- Añadir al final del fichero indice.txt un línea de texto. Añadir los cambios a la zona de intercambio temporal. Hacer un commit de los cambios con el mensaje “Añadido capítulo 5 al índice.”Mostrar quién ha hecho cambios sobre el fichero indice.txt.
![](assets/e2/7.png)

### 3 Exercici desfer canvis


- Eliminar la última línea del fichero indice.txt y guardarlo. Comprobar el estado del repositorio.
![](assets/e3/1.png) 

- Deshacer los cambios realizados en el fichero indice.txt para volver a la versión anterior del fichero. Volver a comprobar el estado del repositorio.
![](assets/e3/2.png)

- Eliminar la última línea del fichero indice.txt y guardarlo. Añadir los cambios a la zona de intercambio temporal. Comprobar de nuevo el estado del repositorio. 
![](assets/e3/3.png)

- Quitar los cambios de la zona de intercambio temporal, pero mantenerlos en el directorio de trabajo. Comprobar de nuevo el estado del repositorio. 
![](assets/e3/4.png)


- Eliminar la última línea del fichero indice.txt y guardarlo. Eliminar el fichero capitulos/capitulo3.txt. Añadir un fichero nuevo captitulos/capitulo4.txt vacío. Añadir los cambios a la zona de intercambio temporal. Comprobar de nuevo el estado del repositorio.
![](assets/e3/5.png)

- Quitar los cambios de la zona de intercambio temporal, pero mantenerlos en el directorio de trabajo. Comprobar de nuevo el estado del repositorio. Deshacer los cambios realizados para volver a la versión del repositorio. Volver a comprobar el estado del repositorio.
![](assets/e3/6.png)

- Eliminar la última línea del fichero indice.txt y guardarlo. Eliminar el fichero capitulos/capitulo3.txt. Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje “Borrado accidental.” Comprobar el historial del repositorio. Deshacer el último commit pero mantener los cambios anteriores en el directorio de trabajo y la zona de intercambio temporal. Comprobar el historial y el estado del repositorio. Volver a hacer el commit con el mismo mensaje de antes. Deshacer el último commit y los cambios anteriores del directorio de trabajo volviendo a la versión anterior del repositorio. Comprobar de nuevo el historial y el estado del repositorio.
![](assets/e3/7.png)


### 4 Exercici gestió de branques
- Crear una nueva rama bibliografia y mostrar las ramas del repositorio.
![](assets/e4/1.png)
- Crear el fichero capitulos/capitulo4.txt y añade texto. Añadir los cambios a la zona de intercam- bio temporal. Hacer un commit con el mensaje “Añadido capítulo 4.” Mostrar la historia del repositorio incluyendo todas las ramas.
![](assets/e4/2.png)
- Cambiar a la rama bibliografia. Crear el fichero bibliografia.txt. Añadir los cambios a la zona de in- tercambio temporal. Hacer un commit con el mensaje “Añadida primera referencia bibliográfica.” Mostrar la historia del repositorio incluyendo todas las ramas.
![](assets/e4/3.png)

- Fusionar la rama bibliografia con la rama master. Mostrar la historia del repositorio incluyen- do todas las ramas. Eliminar la rama bibliografia. Mostrar de nuevo la historia del repositorio incluyendo todas las ramas.
![](assets/e4/4.png)
- Crear la rama bibliografia. Cambiar a la rama bibliografia. Cambiar el fichero bibliografia.txt. Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje “Añadida nueva referencia bibliográfica.” Cambiar a la rama master. Cambiar el fichero bibliografia.txt. Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje “Añadida nueva referencia bibliográfica.” Fusionar la rama bibliografia con la rama master. Resolver el conflicto dejando el fichero bibliografia.txt. Añadir los cambios a la zona de intercambio temporal y hacer un.Commit con el mensaje “Resuelto conflicto de bibliografía.” Mostrar la historia del repositorio incluyendo todas las ramas.
![](assets/e4/5.png)

### 5 Exercici de repositoris remots
- Crear un nuevo repositorio público en GitHub con el nombre libro-git. Añadirlo al repositorio local del libro. Mostrar todos los repositorios remotos configurados.
![](assets/e5/1.png)

- Añadir los cambios del repositorio local al repositorio remoto de GitHub. Acceder a GitHub y comprobar que se han subido los cambios mostrando el historial de versiones.

- Colaborar en el repositorio remoto libro-git de otro usuario. Clonar su repositorio libro-git. Añadir el fichero autores.txt que contenga el nombre del usuario y su correo electrónico. Añadir los cambios a la zona de intercambio temporal. Hacer un commit con el mensaje “Añadido autor.” Subir los cambios al repositorio remoto

- Hacer una bifurcación del repositorio remoto asalber/libro-git en GitHub. Clonar el repositorio creado en la cuenta de GitHub del usuario. Crear una nueva rama autoria y activarla. Añadir el nombre del usuario y su correo al fichero autores.txt. Añadir los cambios a la zona de intercambio temporal. Hacer un commit con el mensaje “Añadido nuevo autor.” Subir los cambios de la rama autoria al repositorio remoto en GitHub. Hacer un Pull Request de los cambios en la rama autoria.
![](assets/e5/2.png)
