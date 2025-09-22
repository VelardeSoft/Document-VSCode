# Deploy desde visual Studio Code a GitHub

Primero creamos una carpeta y abrimos en Visual Studio Code, como paso 2 creamos un archivo README.md, este archivo puedo o no contener información pero ya es suficiente para desplegar a GitHub, antes de hacer deploy, verficar que debemos estar inicializa nuestra cuenta de GitHub en VSCode, primer paso: 

```sh
git init
```

Una vez inicializado, agregamos nuestros archivos

```sh
git add .
```

Agregamos nuestra primera commit

```sh
git commit -m "mi first commit"
```

Toda ejecución a sido de manera local, ahora pasamos a crear un repositorio en GitHub, 

New Repository

```sh
git branch -M master
```

Ahora inyectamos nuestra dirección de GitHub

```sh
git remote add origin https://github.com/VelardeSoft/Document-VSCode.git
```

Finalmente, hacemos push a la rama master

```sh
git push -u origin master
```


Hasta aquí, ya se desplego una primera versión. Ahora toca subir la segunda versión con otras informaciones agregadas: 

Si hay nuevas archivo: 

```sh
git add .
```

```sh
git commit -m "Segunda versión"
```

```sh
git push origin master
```

Final del proyecto basico como puedes hacer deploy. Gracias

```sh
git push -f origin master
```