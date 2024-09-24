# GitHub Activity CLI

Este es un programa de línea de comandos (CLI) que permite obtener y mostrar la actividad reciente de un usuario de GitHub utilizando la API de GitHub.

## Requisitos

- [Node.js](https://nodejs.org/) instalado en tu máquina.

## Instalación

1. Clona este repositorio o descarga el archivo `github-activity.js`.
2. Navega al directorio donde se encuentra el archivo.

## Uso

1. Abre tu terminal.
2. Ejecuta el siguiente comando:

   ```bash
   node github-activity.js
   ```

3. Cuando se te pida, ingresa el nombre de usuario de GitHub para el cual deseas ver la actividad.

   ````
   Por favor, ingresa el nombre de usuario de GitHub:
   ```

4. El programa mostrará la actividad reciente del usuario en la terminal.

## Ejemplo de Salida

```
Pushed 3 commits to kamranahmedse/developer-roadmap
Opened a new issue in kamranahmedse/developer-roadmap
Starred kamranahmedse/developer-roadmap
```

## Manejo de Errores

- Si el nombre de usuario no es válido o no se encuentra, el programa mostrará un mensaje de error correspondiente.
- Si hay un problema al conectarse a la API de GitHub, se mostrará un mensaje de error.

## Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de hacer un fork y enviar un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

https://roadmap.sh/projects/github-user-activity