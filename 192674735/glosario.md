# Taller 1

> **Nombre**: Braulio Lobo
> **RUT**: 19.267.473-5

## Conceptos
**1. Control de versiones (VC)**  
Los controles de versiones o VC (por sus siglas en ingles Version Controller) son diversos programas que sirven para organizar y gestionar las diversas versiones de un proyecto de software. Esto ayuda a los equipos de desarrollo mantener sus proyectos seguros y organizados, de forma que si ocurre un imprevisto, se pueda volver a una vercion funcional y operativa. ([fuente](https://es.wikipedia.org/wiki/Programas_para_control_de_versiones))

**2. Control de versiones distribuido (DVC)**  
Un controlador de versiones distribuidos permite al equipo de desarrollo tener un controlador de versiones e una red no local. Esto facilita el desarrollo a distancia y lo hace mas seguro. ([fuente](https://es.wikipedia.org/wiki/Control_de_versiones_distribuido))

**3. Repositorio remoto y Repositorio local**  
Los repositorios remotos son el historial de versiones en internet de un proyecto en especifico. Por otro lado, el repositorio local es un historial de versiones en una red local. ([fuente](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos))

**4. Copia de trabajo / Working Copy**  
Una copia de trabajo es un clon del proyecto actual con todos los ficheros listos para ser usados. Esto permite tener un respaldo para solucionar cualquier imprevisto. ([fuente](https://www.jetbrains.com/help/clion/configuring-the-format-of-the-local-working-copy.html))

**5. Área de Preparación / Staging Area**  
El área de trabajo es un archivo que contiene información de los archivos del próximo commit. También se le llama *indice*, pero es mas común llamarlo área de preparación. ([fuente](https://git-scm.com/book/es/v1/Empezando-Fundamentos-de-Git)).

**6. Preparar Cambios / Stage Changes**  
Son los archivos que serán guardados en el repositorio. Éstos se agregan al área de preparación utilizando el comando ``git add {filename}``
([fuente](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Guardando-cambios-en-el-repositorio))

**7. Confirmar cambios / Commit Changes**  
Es la acción de actualizar los archivos del repositorios que se encuentran en la zona de preparación de cambios, es decir, todos aquellos archivos que estén siendo rastreados por el controlador de versiones. Esto se hace mediante el comando ``git commit``
([fuente](https://git-scm.com/book/es/v2/Fundamentos-de-Git-Guardando-cambios-en-el-Repositorio))

**8. Commit**  
Comando utilizado para actualizar los archivos del repositorio, es decir, permite confirmar los cambios.  
Mediante la utilización de la linea ``git commit -m {mensaje}`` se puede agregar un mensaje al commit, lo que permite tener una descripción de los cambios realizados.
([fuente](https://git-scm.com/book/es/v2/Fundamentos-de-Git-Guardando-cambios-en-el-Repositorio))

**9. clone**  
Comando que permite descargar una copia de un repositorio en especifico. Su utilización es ``git clone {url}``. ([fuente](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Obteniendo-un-repositorio-Git))

**10. pull**  
Intenta mezclar la información del último repositorio que se clonó con la información del repositorio local.
([fuente](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos))

**11. push**  
El comando ```git push``` realiza una actualización del repositorio remoto con el contenido del repositorio local. Esta actualización del repositorio remoto queda marcada con el mensajes que se ha colocado en el commit del repositorio local. 
([fuente](https://www.atlassian.com/git/tutorials/syncing/git-push))

**12. fetch**
El comando ```git fetch [repo-remoto]``` recupera los datos almacenados en el repositorio remoto, descargando los datos faltantes, pero no haciendo una combinación de estos. Esto ultimo quiere decir que no toca los archivos que se hayan modificado en el repositorio local. ([fuente](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos))

**13. merge**
El comando ```git marge [branch]``` permite realizar una mezcla de la rama actual con la rama ingresada (```branch```) permitiendo una actualización rápida y segura de los archivos que depende todo el proyecto. ([fuente](https://git-scm.com/book/es/v1/Ramificaciones-en-Git-Procedimientos-básicos-para-ramificar-y-fusionar))

**14. status**
El comando ```git status``` permite ver el estado de los archivos del repositorio local en comparación con el repositorio remoto. Por ejemplo, si se ha realizado un cambio en un archivo contenido en el repositorio local, ```git status``` nos indicará que dicho archivo necesita ser agregado para el commit. ([fuente](https://git-scm.com/book/es/v2/Appendix-B%3A-Comandos-de-Git-Seguimiento-Básico))

**15. log**
Permite ver el histórico de todos las confirmaciones del repositorio (commit). ([fuente](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Viendo-el-histórico-de-confirmaciones))

**16. checkout**
Permite saltar de una rama a otra. Se utiliza de la forma ``git checkout -b [rama]``, donde ``[rama]`` es la rama a la cual se quiere saltar. ([fuente](https://git-scm.com/book/es/v1/Ramificaciones-en-Git-Procedimientos-básicos-para-ramificar-y-fusionar))

**17. Rama / Branch**
Las ramas (Branch) son estados paralelos del proyecto. Por ejemplo, si se quiere hacer una prueba del sistema con otro componente, se crea una rama aparte de la original, en caso de que el componente resulte ser ineficiente o no convincente, solo se destruye esta rama- ([fuente](https://git-scm.com/book/es/v1/Ramificaciones-en-Git-Procedimientos-básicos-para-ramificar-y-fusionar))

**18. Etiqueta / Tag**
Las etiquetas son marcas en el historial de versiones del controlador de versiones. Estas marcas permiten resaltar versiones importantes para el proyecto (Como versiones estables, o versiones comerciales). ([fuente](https://git-scm.com/book/es/v2/Fundamentos-de-Git-Etiquetado))