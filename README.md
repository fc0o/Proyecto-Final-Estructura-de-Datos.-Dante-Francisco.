# Proyecto Final Estructura de Datos. Por: Aline, Dante, Francisco.

Para el proyecto se decidio crear un codigo que pudiera manejar una lista de contactos junto con funciones que permitan su modificación y visualización.

## Estructuras de datos usadas
1.- Lista ligada: Historial de acciones ejecutadas

2.- Arbol: Obtener contactos ordenados

3.- Tabla hash: A cada contacto se le asigna un número de teléfono

4.- Stack: Almacenar las modificaciones realizadas para deshacer estas acciones

5.- Recientes: Guardar las ultimas 5 busquedas realizadas

## Instrucciones de ejcución
Requisitos: Versión de Python 3.7 o superior
Clona el repositorio, abre jupyter notebook y selecciona el archivo Lista-de-contactos.ipynb
Al ejecutar el codigo aparecera un menu con opciones que van del 1 al 12. Escribe el número deseado dentre de ese rango.
A continuación se presenta la lista de funciones junto con sus instrucciones

1.- Agregar contacto: Escribe el nombre, presiona enter, escribe el número de teléfono de tal persona, presiona enter.

2.- Buscar contacto: Escribe el nombre del contacto cuyo numero se desea buscar y presiona enter

3.- Eliminar contacto: Escribe el nombre del contacto que se desea eliminar.

4.- Modificar contacto: Escribe el nombre del contacto que quieres modificar, presiona enter y escribe el nuevo número de teléfono del contacto elegido. 

5.- Mostrar contactos ordenados: Al escoger la opción 5 se muestra la lista de contactos en orden alfabéticco

6.- Mostrar historial: Al escoger la opción 6 se muestra el historial de las acciones realizadas

7.- Deshacer(undo): Rehace la ultima acción

8.- Últimas busquedas: Al escoger la opción 8 se muestras las ultimas 5 acciones realizadas

9.- Buscar por prefrijo: Escribe el inicio de un nombre para buscar todos los contactos con ese mismo inicio

10.- Exportar contactos a archivo: Exporta la lista de contactos como archivo csv

11.- Importar contactos desde archivo: Escribe el nombre del archivo donde estan los contactos que se desean importar. Dede ser un archivo csv, si es de la manera "nombre.csv", escribir "nombre.csv". El archivo csv debe ser de la forma "nombre,número"

12.- Salir: Detiene la ejecución del código
