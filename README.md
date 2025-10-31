# Git y GitHub

Este informe explica los **principales comandos de Git** y el **proceso paso a paso** para crear un repositorio, realizar cambios y subirlos a **GitHub**.  
Además, incluye ejemplos y espacio para agregar capturas de pantalla como evidencia del proceso.

---

## Principales comandos de Git

| Comando | Descripción |
|----------|-------------|
| `git init` | Inicializa un nuevo repositorio local en la carpeta actual. |
| `git status` | Muestra el estado actual de los archivos del proyecto. |
| `git add .` | Agrega todos los archivos modificados al área de preparación (staging). |
| `git commit -m "mensaje"` | Guarda los cambios con un mensaje descriptivo. |
| `git branch` | Muestra las ramas disponibles en el repositorio. |
| `git checkout -b nombre-rama` | Crea una nueva rama y cambia a ella. |
| `git remote add origin URL` | Conecta el repositorio local con uno remoto en GitHub. |
| `git push -u origin main` | Envía los cambios al repositorio remoto en la rama principal. |
| `git pull` | Descarga y fusiona los últimos cambios del repositorio remoto. |

---

## Paso a paso para subir un proyecto a GitHub

1. **Crear carpeta del proyecto**
   ```bash
   mkdir mi_proyecto
   cd mi_proyecto
   ```
2. **Inicializar Git**

 ``` bash
    git init
```

3. **Agregar archivos**

 ``` bash
    git add .
 ```

4. **Guardar los cambios (commit)**
``` bash
    git commit -m "Primer commit del proyecto"
```

5. **Crear un repositorio en GitHub**

 - Ingresar a GitHub

 - Clic en New repository

 - Asignar un nombre y crea el repositorio vacío.

 6. **Conectar el repositorio local con GitHub**
``` bash
  - git remote add origin https://github.com/Nombre_del_usuario/git_and_github.git
```

7. **Enviar los cambios**
``` bash
  - git push -u origin main
```

8. **Verificar en GitHub**
  - Revisar que los archivos aparezcan en el repositorio.
