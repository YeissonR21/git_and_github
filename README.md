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
   <img width="305" height="45" alt="image" src="https://github.com/user-attachments/assets/16aa4d32-4d01-4cd6-88a2-57b1437da108" />

2. **Inicializar Git**

 ``` bash
    git init
```
<img width="655" height="95" alt="image" src="https://github.com/user-attachments/assets/92c9fc9c-ff10-4360-9b0f-b97782db6ab9" />
<img width="418" height="46" alt="image" src="https://github.com/user-attachments/assets/19ef7a5c-cfcf-4c0f-851d-388d82056ceb" />
<img width="1385" height="440" alt="image" src="https://github.com/user-attachments/assets/2c73f2f6-9a1c-4cf2-8d88-93f2017c88ff" />

3. **Agregar archivos**

 ``` bash
    git add .
 ```
<img width="425" height="225" alt="image" src="https://github.com/user-attachments/assets/354cb187-a51d-4e92-9bab-b83ebaaabcd6" />

4. **Guardar los cambios (commit)**
``` bash
    git commit -m "Primer commit del proyecto"
```
<img width="433" height="103" alt="image" src="https://github.com/user-attachments/assets/454f1ebc-8733-4efb-ada1-297d9782e93b" />

5. **Crear un repositorio en GitHub**

 - Ingresar a GitHub

 - Clic en New repository
<img width="1838" height="151" alt="image" src="https://github.com/user-attachments/assets/3b685619-4014-407a-a219-44a4ab2b88dc" />

 - Asignar un nombre y crea el repositorio vacío.

 6. **Conectar el repositorio local con GitHub**
``` bash
  - git remote add origin https://github.com/Nombre_del_usuario/nombre_del_repositorio.git
```
<img width="731" height="56" alt="image" src="https://github.com/user-attachments/assets/2431ba4e-37b1-4677-aeb4-22f8e4f67b62" />

7. **Enviar los cambios**
``` bash
  - git push -u origin main
```
<img width="581" height="195" alt="image" src="https://github.com/user-attachments/assets/5e21dd66-05a5-435a-982e-b4dc3aec0815" />

8. **Verificar en GitHub**
  - Revisar que los archivos aparezcan en el repositorio.
<img width="1164" height="208" alt="image" src="https://github.com/user-attachments/assets/8cc081cd-e734-4d60-a1b4-0057272b8ddd" />
