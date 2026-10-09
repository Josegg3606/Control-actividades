1. Flujo colaborativo
Supón que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos:
Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos. Agrega cualquier
operación que consideres necesaria.
R=ahi los pasos son los soguientes 
1;primero es un fork,
2;despues de eso es un pull request, 
3;ya despues de eso ahora si sigue el clone en tu computadora,
4;despues que ya acabemos sigue un merge,
5;ahi despues hacemos una review, 
6;hacemos un commit,
7;y terminamos subiendolo con un push 

2. Fork y Clone
Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es correcta
y explica la diferencia entre Fork y Clone.
R= no crea una copia, osea si crea una copia pero no en mi cuenta de github si no que la laptop es donde se crea la copia, asi que respondiendo la pregunta es INCORRECTO

3. Pull Request
Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman parte
del repositorio original? ¿Qué debe ocurrir para incorporarlos?
R=si ya son parte del proyecto, pero faltaria una serie de pasos o comandos para poder ver los cambios, y los cambios son los siguientes
git switch main
git pull origin main
git log --oneline

4. Request Changes
El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear
otro Pull Request y qué ocurre cuando realizas nuevamente push.
R=Debo leer los comentarios del propietario, corregir los cambios solicitados en mi rama y luego guardar las correcciones en un nuevo commit. Después hago push a esa misma rama. No necesito crear otro Pull Request: el Pull Request existente se actualiza automáticamente con los nuevos commits y el propietario puede revisarlo de nuevo.

5. Merge y repositorio local
Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no
contiene los cambios. Explica por qué sucede y qué operación debe realizarse.
R=cuando no tiene ningun cambio siginifica que no ha hecho ningu commit y no ha hecho ningun push por eso no se notan los cambios 

6. Sync Fork
Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta
utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.
Registra este cambio en un cuarto commit con un mensaje descriptivo y súbelo a github.
R=la herramienta que debo de utilizar es un push y el url del commit para poder actualizarlo, la diferecnia de ellos 3 es que cada uno hace una tarea difente pero que cada uno tiene que ver cono los demas 