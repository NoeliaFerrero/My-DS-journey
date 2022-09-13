# Activar extensiones en Jupyter Notebooks
------

En este repo voy a mostrar una lista de extensiones que se deberían instalar en Jupyter Notebooks para poder escribir código Python más fácilmente. 

Las extensiones incluyen lo siguiente: 

- Atajo para mover celdas (Move Selected Cells) 

- Autocompletar palabras (Hinterland) 

- Atajo para correr celdas (Runtools) 

- Buscar archivos en Jupyter Notebook (Tree filter) 

- Ocultar Input (Hide input + Hide input all) 

- Plantilla de código en Jupyter Notebook (Snippet Menu) 

- Tabla de contenido (Table of Content 2) 

- Borrador en Jupyter Notebook (Scrathpad) 

- Codefolding 

- Inspector de variable (Variable inspector) 

- Traducir texto en Jupyter Notebook (nbTranslate) 

- Cambiar de tema: C:\Users\Administrador>pip install jupyterthemes

Para ver los temas disponibles, tipear en la línea de comando: C:\Users\Administrador>jt –l
Una vez que se escoge el tema, tipear en la línea de comando:  
C:\Users\Administrador>jt –t onedork –T –N
Luego enter y refrescamos el notebook para aplicar los cambios
Si se quieren hacer los cambios de tema dentro del notebook, se escribe en una línea de código:
!jt –l y luego !jt –t (nombre del tema) –T –N -kl

💻 Código para instalar Jupyter Notebooks: 

1. pip install jupyter_contrib_nbextensions 
2. jupyter contrib nbextension install 
Pueden correrlo primero 1 y luego 2 o juntos con el símbolo && como se muestra en el video

https://www.youtube.com/watch?v=JTpZPJRW-GI

