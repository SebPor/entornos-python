# Entonrnos de Python
---
## Indice
1.[Crear y gestionar entornos de Python](#1-crear-y-gestionar-entornos-de-python)

2.[Instalación y uso de Anaconda](#instalación-y-uso-de-anaconda)
   
3.[Diferencias entre anaconda, colab y entornos de Python](#diferencias-entre-anaconda-colab-y-entornos-de-python)


## 1. Crear y gestionar entornos de Python
Para crear un entorno de Python lo primero que tenemos que haces es instalar Python, para ello podemos hacerlo desde la tienda de Microsoft Store.

Una vez tenemos Python instalado para crear un enviroment tenemos que poner el siguiente comando: 
```
python -m venv (nombre del entorno)-env
```
Una vez creado el entorno si lo queremos activar tenemos que ejecutar el siguiente comando en Windows:
```
(nombre del entorno)\Scripts\activate
```
En caso de que nos salga un error de que los scripts no estan habilitados en el sistema tenemos que escribir el siguiente comando con modo administrador:
```
Set-ExecutionPolicy Unrestricted
```
Una vez ya tenemos creado el entorno podemos salir de el escribiendo `deactivate` en el terminal.

Probamos a instalar algún paquete para probar el entorno, en este caso vamos a instalar pandas con el siguiente comando:
```
pip install pandas
```
Para listar los paquetes que hay instalados en el entorno podemos escribir el siguiente comando:
```
pip list
```
Si todo ha salido bien deberiamos ver esto:
![Texto](./img/Lista%20entorno.PNG)

---
## Instalación y uso de Anaconda
Cosas

---

## Diferencias entre anaconda, colab y entornos de Python
cosas

---

