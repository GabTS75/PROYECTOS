## CREAR UN REPOSITORIO EN GITHUB USANDO COMANDOS

- En GitHub vamos a "repositorios" y hacemos click en "nuevo" (new)
- A continuación le damos un "NOMBRE_ejemplo" y lo dejamos como "público" (siempre!, de momento)
- Finalmente le damos a "crear repositorio" (create)

### Ahora "copiamos" lo siguiente:
- git remote add origin https://github.com/USUARIO_ejemplo/Nombre_ejemplo.git
- En VSCode abrimos la terminal (PowerShell o GitBash) y escribimos: git init (enter)

### Luego pegamos la línea que copiamos anteriormente:
- git remote add origin https://github.com/USUARIO_ejemplo/Nombre_ejemplo.git (enter)

### Ahora el PADRE NUESTRO!!!

- Utilizaremos el comando: git add . (enter)
- Luego añadimos un comentario: git commit -m "comentario de cualquier modificación" (enter)
- Finalmente ejecutamos: git push origin master (enter) y si fallara usar "main" en lugar de "master"
- Actualizamos GitHub y veremos que todos los cambios se han generado correctamente, es decir, la creación del repositorio y sus comentarios respectivos.
- Si modificamos en VSCode debemos "guardar" (CTRL + S) y seguidamente repetir el PADRE NUESTRO
- $ git add .
- $ git commit -m "xxxxxxxxxxxxxxxxxx"
- $ git push origin master (o "git push origin main" si falla)
