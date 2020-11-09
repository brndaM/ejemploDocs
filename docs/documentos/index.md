># Instalar Docsify.

 Se recomienda instalar **docsify-cli** globalmente, lo que ayuda a inicializar y obtener una vista previa del sitio web localmente.
 ```node.js
 npm i docsify-cli -g
 ```
 >## Inicializar.

una ves instalado Docsify lo segundo que debes hacer es inicializar Docsify en tu subdirectorio.
Si desea escribir la documentación en el subdirectorio **./docs**, puede usar el comando **init**.
```bash
docsify init ./docs
```
>## Contenido 
Después de que se complete **init**, puede ver la lista de archivos en el subdirectorio **./docs.**

* **index.html** como el archivo de entrada
* **README.md** como la página de inicio (la principal)
* **.nojekyll** impide que las páginas de GitHub ignoren los archivos que comienzan con un guión 

Puede actualizar la documentación en **./docs/README.md**

>## Vista Previa

Ejecute el servidor local con **docsify serve**. Puede obtener una vista previa de su sitio en su navegador en **http: // localhost: 3000.**

```bash
docsify serve docs
```

