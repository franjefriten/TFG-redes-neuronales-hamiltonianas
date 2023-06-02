## Aplicaciones de las Redes Neuronales en la parametrización de hamiltonianos y lagrangianos

Trabajo de final de grado, Grado en Física, Universidad de Alicante, 2022-2023

Autor:

* Francisco J. Frías ([fj.friastenza@gmail.com]())

Este repositorio contiene los programas que se discuten en el trabajo de final de grado sobre Redes Neuronales Hamiltonianas (HNN's) en forma de notebooks de Python.

1. Oscilador armónico
2. Péndulo simple
3. Péndulo disipativo
4. Péndulo doble
5. Problema de los dos cuerpos

### Instalación

#### En máquina local

El paquete posee un archivo llamado _requirements.txt_. Síganse estos pasos.

1. Créese una carpeta específica para los códigos
2. Use el siguiente comando `git clone [URL]` o bien descarguelos en un .zip y descomprímalos
3. Use el siguiente comando estando en la dirección de memoria del repositorio en su máquina
   3.1. `python -m venv .env`
   3.2. `C:\Users\...\.env\Scripts\Activate.ps1`
   3.3. `python -m pip install -r requirements.txt`
4. Seleccione el entorno vitual como el Kernel por defecto, se puede hacer arriba a la derecha en Visual Studio Code tras abrir un archivo .ipynb o desde Jupyter también es posible.

La ejecución de los programas depende enteramente de la capacidad de su máquina.

De esta forma tiene todas las librerías en un entorno virtual de Python y no se mezclará con las librerías de su máquina local en el sistema.

#### En Google Colab

1. Sencillamente descargue en .zip o clone como en el paso anterior en su máquina.
2. Teniendo la extensión de Google Collab en su Google Drive, cree un archivo vacío y suba el archivo .ipynb que desee usar
3. Google Collab se encargará del resto, si hay algún problema con las librerías deberá instalarlas aunque por lo general no será necesario

La ejecución de los programas depende enteramente de la capacidad de Google y por lo general no suele dar problemas. Aunque siempre tenga vigilada la ventada en caso de que de algún error imprevisto. Cabe destacar que es trabajo se ha realizado con una máquina con las siguientes especificaciones.

1. Intel Core i5-1035G4 1.1GHz
2. 8 GB de RAM
3. 256 GB de disco duro
4. Microsoft Windows 10
