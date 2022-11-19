# document-model

### Imagenes
Si las imagenes se encuentran en **/img/** unicamente es necesario colocar el nombre de la imagen.

### Bibliografia
vaya al archivo referencias.bib y coloque sus fuentes en el formato establecido.

### Cubierta
La cubierta del trabajo se encuentra en el archivo cover.tex, modifiquelo para que quede a su gusto

### Instalación
Si tiene Python instalado puedo optar por instalar [texpj](https://pypi.org/project/texpj/) y así tener una forma sencilla de administrar
plantillas, si ya tiene instalado texpj ejecute los siguiente:

```
texpj install BenyaminGaleano/document-model NOMBRE_PLANTILLA "documento base para investigaciones"
```

Para que funcione se necesita que tenga instalado **git**.

### Windows
Por el momento no he hecho instaladores para windows así que toca manual.

Descargue [Utilidades](https://github.com/BenyaminGaleano/utilidades.git) y coloque los archivos en la misma carpeta de su proyecto.

### Linux
Puede utilizar estos comandos y ahorrarse acciones:
- **bin/clean** limpia todos los archivos no necesarios en el proyecto.
- **bin/update** descarga [Utilidades](https://github.com/BenyaminGaleano/utilidades.git) y coloca el archivo en el scope.
- **bin/create nombre_carpeta** crea un nuevo reporte a partir del actual, limpia y actualiza [Utilidades](https://github.com/BenyaminGaleano/utilidades.git) si se lo permite, además abre la carpeta que se creo (se crea en la carpeta padre de donde se ejecutó el script) y abre texstudio en el proyecto si lo tiene instalado.
- **bin/open** para abrir el proyecto si en dado caso lo dejó pendiente.


