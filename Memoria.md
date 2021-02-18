

### ExamenB

#### 1. Crea una carpeta que será la carpeta de trabajo del examen. Llámala examen-b  
mkdir examen-b  

#### 2. Inicializa el repositorio  
git init  

#### 3.Crea un archivo llamado examenb.html con el contenido

#### 4. Crea una carpeta llamada contenidos y dentro de esta carpeta dos ficheros llamados

#### 5. Pasa los ficheros y directorios a preparado  
git add --all  

#### 6. Confirma los ficheros con un commit “Inicial commit”  
git commit -m "Inicial commit"  

#### 7. Mira el estado del proyecto  
git status  

#### 8. Modifica el texto del ultimo commit poniendo “ Contenidos 1,2 e índice“  
git commit --amend (esto abre un editor de texto donde cambiaremos el nombre del commit, lo guardaremos y lo cerraremos)  

#### 9. Modifica el fichero html.txt eliminando todo su contenido  

#### 10. Pasa a preparado de nuevo el fichero html.txt  
git add --all  

#### 11. Realiza otra confirmación con comentario “Eliminado texto de contenido html”  
git commit -m "Eliminado texto de contenido html"  

#### 12. Visualiza el log de todo el proyectos  
git log  

#### 13. Vuelve atrás al commit inicial de “Contenidos 1,2 e índice”  
git checkout dc8914953ad2690ed7b3ea8618782d3388f1dce7

#### 14. Vuelve al estado final del proyecto (antes de la vuelta atrás)  
git checkout --  

### 15. Crea un repositorio público en tu GITHUB y haz un push de todo el proyecto.  
git remote add origin https://github.com/Miquel-Mauri/ExamenB.git  
git push -all
