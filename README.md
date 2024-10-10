# Ejercicio-branch

## Clonacion de repositorio

```code
bae2@jpexposito-VirtualBox:~/Documentos$ git clone https://github.com/materancode/Ejercicio-branch.git
Clonando en 'Ejercicio-branch'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Recibiendo objetos: 100% (3/3), listo.


```
## Creamos un nuevo Branch o Rama para los nuevos cambios

```code
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git add Ejercicio2.java 
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git branch 
ejercicio1-branch          HEAD                       origin/ejercicio1-branch   origin/main 
ejercicio.java             main                       origin/HEAD                
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git branch Ejercicio2.java
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ code .
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git checkout -b
error: switch `b' requiere un valor
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git checkout -b Ejercicio2.java
fatal: Una rama llamada 'Ejercicio2.java' ya existe.
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ ^C
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ 


```

## Se incluye el commit

```code 
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git add README.md
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git commit -m "Se añade el ejercicio3"
[Ejercicio3.java 4118671] Se añade el ejercicio3
 1 file changed, 4 insertions(+), 1 deletion(-)
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ 

```
## Subimos los cambios al repositorio

```code
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git push --set-upstream origin ejercicio3-branch  
Enumerando objetos: 12, listo.
Contando objetos: 100% (12/12), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (10/10), listo.
Escribiendo objetos: 100% (10/10), 1.44 KiB | 493.00 KiB/s, listo.
Total 10 (delta 4), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (4/4), completed with 1 local object.
remote: 
remote: Create a pull request for 'ejercicio3-branch' on GitHub by visiting:
remote:      https://github.com/materancode/Ejercicio-branch/pull/new/ejercicio3-branch
remote: 
To https://github.com/materancode/Ejercicio-branch
 * [new branch]      ejercicio3-branch -> ejercicio3-branch
Rama 'ejercicio3-branch' configurada para hacer seguimiento a la rama remota 'ejercicio3-branch' de 'origin'.



bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git status
En la rama main
Tu rama está adelantada a 'origin/main' por 5 commits.
  (usa "git push" para publicar tus commits locales)

nada para hacer commit, el árbol de trabajo está limpio
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git pusj
git: 'pusj' no es un comando de git. Mira 'git --help'.

El comando más similar es
        push
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ git push
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (3/3), 444 bytes | 444.00 KiB/s, listo.
Total 3 (delta 1), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/materancode/Ejercicio-branch
   f7f199a..a63cf2a  main -> main
bae2@jpexposito-VirtualBox:~/Documentos/Ejercicio-branch$ 

```