# Ejecución del Proyecto
Este proyecto implementa un algoritmo de búsqueda A* para encontrar la ruta más corta en una red de estaciones, considerando un número máximo de transbordos.

## Requisitos
* Python 3.x
* Biblioteca "heapq" (incluida en la biblioteca estándar de Python)
## Instrucciones de Ejecución
### Clonar el repositorio:
```
git clone https://github.com/nesvas99/ejercicio-tm.git
cd tu_repositorio
```
### Definir las rutas:
* Abre el archivo principal del proyecto y define las rutas entre estaciones en la lista "rutas" en el formato "(desde, hacia, tiempo, ruta)".
### Ejecutar el script:
* Ejecuta el script principal:
```
python nombre_del_script.py
```
### Ingresar datos:
* Ingresa la estación de origen, la estación de destino y el número máximo de transbordos permitidos cuando se te solicite.
## Ejemplo de Uso
```
Ingrese la estación de origen: A
Ingrese la estación de destino: B
```
## Resultados
El script imprimirá la mejor ruta encontrada, el tiempo total del trayecto, las rutas utilizadas y las estaciones de transbordo.
