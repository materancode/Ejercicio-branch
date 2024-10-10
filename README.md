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