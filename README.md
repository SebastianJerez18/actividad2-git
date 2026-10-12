Actividad 2: Hands on, configuración de herramientas (Git y GitHub)

Nombre: Juan Sebastian Gómez Jerez
Código: 46962

Descripción
Repositorio de la Actividad 2. Contiene un tutorial de Git por cada capítulo del libro Pro Git (https://git-scm.com/book/es/v2), elaborado en Word y exportado a PDF, además de archivos de práctica para el uso de comandos básicos de Git.

Proceso seguido
1. Creación de la cuenta de GitHub y del repositorio `actividad2-git`.
2. Instalación y configuración de Git (nombre y correo del usuario).
3. Clonación del repositorio con `git clone`.
4. Elaboración de un documento de Word por capítulo y exportación a PDF.
5. Registro de cambios con `git add` y `git commit`, usando mensajes descriptivos.
6. Envío al repositorio remoto con `git push` al terminar cada capítulo.
7. Práctica de ramas, fusión, renombrado de archivos y exploración de objetos internos.

Contenido del repositorio
| Archivo | Descripción |
|---|---|
| 01-Inicio | Capítulo 1: Inicio (Sobre el control de versiones) |
| 02-Fundamentos-de-Git | Capítulo 2: Fundamentos de Git |
| 03-Ramificaciones-en-Git | Capítulo 3: Ramificaciones en Git |
| 04-Git-en-el-servidor | Capítulo 4: Git en el servidor |
| 05-Git-distribuido | Capítulo 5: Git distribuido |
| 06-GitHub | Capítulo 6: GitHub |
| 07-Herramientas-de-Git | Capítulo 7: Herramientas de Git |
| 08-Personalizacion-de-Git | Capítulo 8: Personalización de Git |
| 09-Git-y-otros-sistemas | Capítulo 9: Git y otros sistemas |
| 10-Entresijos-internos-de-Git | Capítulo 10: Los entresijos internos de Git |
| notas.txt | Archivo de texto de práctica con cambios versionados |
| .gitignore | Ignora los archivos temporales de Word (`~$*`) |

Cada capítulo está disponible en formato ".docx" y ".pdf".

Cambios realizados
- Se modificó `notas.txt` en dos commits para practicar el ciclo `add` y `commit`.
- Se actualizó el tutorial del capítulo 2 con su conclusión.
- Se renombraron los archivos del capítulo 8 con `git mv` para corregir un error de escritura.
- Se agregó un `.gitignore` para evitar subir archivos temporales.

Comandos utilizados
`git clone`, `git status`, `git add`, `git commit`, `git push`, `git diff`, `git log`, `git remote`, `git switch`, `git merge`, `git branch`, `git mv`, `git cat-file`, `git ls-tree`.

