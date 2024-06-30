# CLASE 11 Actividad en Python

<sub>
Hoy vamos a hacer actividad en Python en un día como programadores:</sub>

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 
```sh
mkdir python-final
```
3. Entramos en ella: 
```sh
cd python-final
```
4. Iniciamos el repositorio:
```sh
git init
```
5. Creamos un archivo:
```sh
touch finales.py
```
6. Abrimos VSC:
```sh
code .
```
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
```sh
python -V

python3 -V
```
8. Creamos el entorno virtual en Python:
```sh
python3 -m venv venv #Creamos el entorno virtual
```
9. Activamos el entorno virtual:
```sh
source venv/bin/activate #Activamos el entorno virtual en Linux

venv/scripts/activate #En windows
```
10. Hacemos actualización del pip de Python
```sh
python3 -m pip install --upgrade pip #Actualizamos el pip
```
11. Investigar ¿Qué es el pip y porque lo actualizamos?
    
>Pip es un gestor de paquetes para Python, que se utiliza para instalar, actualizar y gestionar paquetes de software de Python. Es una herramienta fundamental para cualquier desarrollador de Python, ya que permite instalar y actualizar bibliotecas y frameworks de Python de manera sencilla y eficiente.

>¿Por qué es importante actualizar PIP?

Actualizar PIP es importante por varias razones:

>Seguridad:
Las versiones antiguas de PIP pueden contener vulnerabilidades de seguridad que pueden ser explotadas por atacantes malintencionados. Actualizar PIP garantiza que se tengan las últimas correcciones de seguridad y se eviten posibles problemas de seguridad.

>Compatibilidad:
Las nuevas versiones de PIP pueden agregar soporte para nuevos paquetes y características, lo que puede mejorar la compatibilidad con otros paquetes y software.

>Actualizaciones de paquetes:
PIP es responsable de gestionar las bibliotecas y frameworks de Python. Actualizar PIP garantiza que se tengan las últimas versiones de los paquetes instalados, lo que puede mejorar la estabilidad y rendimiento del software.

>Mejora del rendimiento:
Las nuevas versiones de PIP pueden incluir mejoras de rendimiento y eficiencia, lo que puede mejorar el tiempo de respuesta y la productividad del desarrollador.

>Soporte:
Actualizar PIP garantiza que se tenga soporte para las últimas versiones de Python y de los paquetes, lo que puede ser importante para mantener el software actualizado y funcional.

En resumen, actualizar PIP es importante para garantizar la seguridad, compatibilidad, actualizaciones de paquetes, mejora del rendimiento y soporte para las últimas versiones de Python y paquetes.

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.

