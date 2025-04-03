🏆 H-1 (ENVIAR UN COMMIT AL REPOSITORIO REMOTO)


| Hacks   | Details |
|----------|------|
| H-1     | 	Enviar un commit al repositorio remoto   |

1. Crear un nuevo repositorio en github nombre:`git_h_1`.

2. Crear un repositorio local
git init

3. Registrar el repositorio remoto con tú repositorio local
git remote add origin (pegar_la_ruta_del_repositorio_local)

4. Verificamos la ruta remota
git remote -v

5. Crear un archivo llamado lista_de_usuarios.txt
touch lista_de_usuarios.txt

6. Examinar la creación del archivo
ls -l

7. Agregar el archivo lista_de_usuarios.txt al stage(marcarlos para commitear)
git add lista_de_usuarios.txt

8. Verificamos el status
git status

9. Se realiza el commit
git commit -m "feat: add lista_de_usuarios.txt"

10. Verificamos el commit
git log --oneline

11. cambiar el nombre del ambiente (rama)
git branch -M main

12. Hacemos push
git push -u origin main

13. Verificamos el repositorio remoto en github para ver el push enviado
