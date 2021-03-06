# .NET Standard Workshop - Hands on Lab I
En este Lab repasamos los primeros pasos para trabajar con GitHub, una plataforma de desarrollo colaborativo 
para alojar proyectos utilizando el sistema de control de versiones Git.

## 1 - Crear y clonar repositorios

- Ingresar a [GitHub](https://github.com/) y realizar el Sign in o Sign up
- Crear un fork de [netstandard-workshop](https://github.com/matiasdieguez/netstandard-workshop)
- Clonarlo para descargar localmente el fork
```git clone https://github.com/YOUR-ACCOUNT/netstandard-workshop```
- Crear un nuevo repositorio
- Seleccionar VisualStudio como template de .gitignore para omitir archivos no versionables

Si estan utilizando Visual Studio Code, agregar al final de .gitignore
```
# Visual Studio Code
.vscode/*
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json
```

- Seleccionar una licencia para generar el archivo LICENSE
- Clonar tu repositorio localmente
```git clone https://github.com/YOUR-ACCOUNT/REPO-NAME```

## 2 - Agregar archivos, protegerlos y sincronizarlos

- Agregar un archivo README.md para escribir una descripción del proyecto utilizando [Markdown](https://guides.github.com/features/mastering-markdown/) 
- Agregar una carpeta "lib" y una carpeta "test"
- Informar al repo de las adiciones
``` git add .```
- Confirmar cambios
``` git commit -m "comentario" ```
- Publicar cambios
``` git push ```

## 3 - Realizar requests hacia las APIs
- Si tienen instalado Postman importar [Colección APIs en Postman](docs/resources/NETStandard.postman_collection.json)  
- Realizar requests desde Postman para probarlas
