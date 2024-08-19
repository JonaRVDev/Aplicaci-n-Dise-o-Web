## Jonathan Ramirez Vega
### Matricula: 02921581 Carrera: Desarrollo de Software Semestre: 8tavo
Materia:
- Nombre: Diseño de aplicaciones web
- Profesor: Cristopher Gerardo Gaytán Díaz


Markdown:
- Es un lenguaje de marcado sencillo que sirve para agregar formato, vínculos e imágenes con facilidad al texto simple.
- Sirve principalmente para agregar textos y formatearlos en archivos como readmes o notas.


Opciones de etiquetado que ofrece markdown:
- Encabezado: Se utiliza el # para encabezados, hasta el nivel 6
# Titulo 1
# Titulo 2
- Listas: Se utilizan guiones o astericos seguidos de un espacio, asi como se utilizan estas listas.
- Enlaces: Simplemente se copia el texto del enlace. www.google.com
- Enfasis: Para cursiva se utiliza un asterisco al inicio y final de oracion. *text* y para negritas se utilizan dos asteriscos. **text**
- Codigo: Para resaltar una linea de codigo se utlizan las comillas invertidas `. `console.log('hello world')`
- Imagenes: la sintaxis es la siguiente: ![texto_alternativo](ubicacion_de_la_imagen){width=width height=height}


Comnados en Git y como usarlos:
- Verificar el estado de un repositorio local: **git status**
- Agregar archivos individual o localmente: Local: **git add <file-name>**, para agregar todos los cambios de los archivos, o todos los archivos usamos **git add.**
- Agregar comentarios a un commit: **git commmit -m "Comentario del commit"**
- Cargar cambios en el repositorio remoto: Primero tenemos que buscar los cambios mas recientes con **git fetch origin** y despues cargarlos con **git pull 'nombre del branch'**
- Crear ramas: Para crear una rama nueva basandote en la rama actual en la que estas se usa **git checkout -b 'nombre del branch'**
- Explorar ramas: Para cambiar de ramas puedes usar **git checkout 'nombre del branch'** o para revisar todas las branches que hay puedes usar **git branch**
- Eliminar ramas: Se usa **git branch -D 'nombre del branch'**
- Revertir un repositorio a un commit especifico: Utilizamos **git revert --no-commit <commit-hash>..HEAD** el hash del commit es el numero de serie que tiene tu commit
  
