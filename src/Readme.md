# Examen Ramas

**Primero:**
- Hacemos un fork del repositorio original para despues clonarlo en nuestra consola y trabajar en el.

**Segundo:**
- Luego hacemos una rama nueva mediante git branch y la llamamos readme, ahi crearemos este readme.

**Tercero:**
- Iremos a la rama interface y eliminaremos el último commit.
Para ello utilizaremos un git reset para mover la rama al commit anterior. Asi deshacemos el último commit.

**Cuarto:**
- Con un git merge --squash unimos todas las ramas exceptuando la rama readme.

**Quinto:**
- Ahora mediante un release etiquetaremos el commit anterior con un v1.0.

**Sexto:**
- Añadimos el .gitignore a la etiqueta mediante un amend ya que te permite editar un commit ya subido.

**Séptimo:**
- Ahora ya tenemos todo finalizado, subimos todo al repositorio mediante un git push y luego creamos un release mediante.
También hacemos el commit de nuestra rama readme pero no lo mergeamos.