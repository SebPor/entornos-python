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
![Imagen de la lista del entorno](./img/Lista%20entorno.PNG)

---
## Instalación y uso de Anaconda
Lo primero que tenemso que hacer es decargar el instalador desde esta página [Anaconda](https://www.anaconda.com/download). Una vez lo tenemos descargado lo ejecutamos. Los pasos para instalación son muy sencillos solo hay que darle a siguiente en el *Withard* de instalación.

Si todo ha salido bien podemos ejecutar Anaconda y esta es la página principal:
![Imagen de Anaconda](./img/Install%20Anaconda.PNG)

Para crear un cuaderno de Jupiter tenemos que hacer clic en el botón de **Launch** de JupyterLab. Se nos abrirá una Web con la interfaz, pulsamos en un nuevo cuaderno de Python y escribimos el código
```
print("Este es mi primer programa")
```
![Imagen de ejecución Anaconda](./img/ejecución%20junyper.PNG)

---

## Diferencias entre anaconda, colab y entornos de Python
En este apartado vamos a ver los pros y contras de Anaconda, Collab y entornos de Python.

Anaconda
- Pros
  - Esta todo montado
  - Es muy sencillo de utilizar
  - No hay que preocuparse por las versiones
- Contras
  - No es gratuito si quieres hacer un proyecto para una empresa
  - Es un programa muy pesado

Collab
- Pros
  - Esta en la nube
  - Es facil de usar
  - Es colaborativo
- Contras
  - Poca potencia de procesamiento
  
Entornos de Python
- Pros
  - Muy ligeros
  - Personalizables a las necesidades excatas que tengas
- Contras
  - Requiere configuración


