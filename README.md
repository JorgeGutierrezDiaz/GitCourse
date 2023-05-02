# Curso de git y github

Este es el archivo readme donde estara toda la informacion sobre como puedes instalar este proyecto
en tu computador

##Codigos para git en consola

- git init:
  Para iniciar un repositorio dentro de nuestro proyecto

- git add . :
  Añade todos los archivos de nuestro proyecto y hace una foto "local" de los cambios que hicimos
  Esto tambien se hace cada que tengamos un cambio en nuestro proyecto.

- git commit -m "mensaje":
  Creamos una foto de nuestro codigo para posteriormente enviarlo a un repositorio remoto

- git push:
  Enviamos todos los commits que tengamos a nuestro repositorio

- git pull:
  Traemos todos los archivos de nuestro gitHub

  ##Tags

  Los tags nos permiten crear versiones de nuestros proyectos y poder descargarlos
  en archivos .zip

  - git tag versionAlpha -m "versión alpha" :
    Nos genera un tag

  - git log :
    Nos muestra el historial de los tags que hemos hecho con los ID de los commit, esto nos sirve para la siguiente instruccion

  - git tag -a v1.0.0 -m "Versión 1.0.0" id_commit :
    Hacemos una version con el id del commit que nosotros queramos

  - git push --tags :
    Subimos los tags
