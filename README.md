## Python fundamentals for finance

El objetivo del repositorio es que sirva como guía rápida de como podemos utilizar python para analizar datos del mercado bursatil, cuales son los primeros pasos que tenemos que dar, cuales son los problemas típicos y como convertimos estos datos en información.

### Primeros pasos

Lo primero que tenemos que hacer es configurar el ambiente para que podamos trabajar como lo haría un analista de datos. Para esto ya vamos a tener que tener instalado Python y un IDE (de preferencia VScode)

```python
sudo apt install python3-pip
sudo apt install python3-virtualenv
```
*Nota: En windows se debería hacer instalado la versión de pip sin problemas y solo debería instalar virtualenv con un pip install.

Luego nos paramos en el directorio donde vamos a trabajar y creamos el ambiente donde vamos a instalar todas las librerías. En este caso el ambiente se va a llamar env:
```python
virtualenv env
```

Una vez creado el ambiente lo que hacemos es activarlo para luego instalar las librerías necesarias para realizar el análisis
```bash
source env/bin/activate
```

Una vez activo el ambiente vamos a instalar las librerías necesarias para realizar los análisis. Para esto vamos a trabajar con el requirement.txt que dejo en este repositorio:
```python
pip install -r requirements.txt
```

Para abrir el entorno de jupyter para trabajar con las notebooks del repositorio o en caso de querer crear nuestras propios notebooks para otro tipo de análisis lo que vamos a hacer es escribir:
```python
jupyter lab --no-browser
```

Cuando querramos cerrar el ambiente lo que tenemos que escribir en la consola es:
```bash
deactivate
```

### Paquetes instalados

En en la carpeta de docs van a encontrar el archivo "requeriments.txt" con todas las librerías utilizadas en el repositorio. La versión de python utilizada es "Python 3.12.3"

```python
pip freeze > requirements.txt
```

Para luego instalar todas las librerías deberíamos hacer:

```python
pip install -r requirements.txt
```

#### Créditos (citations)

* https://github.com/ranaroussi/yfinance

