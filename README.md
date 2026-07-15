# Biblioteca Personal

Aplicación de consola en Python para gestionar una biblioteca personal de libros (CRUD), siguiendo el patrón Modelo-Vista-Controlador.

## Estructura

- `model/Libro.py` — entidad Libro.
- `view/MainView.py` — menú interactivo por consola.
- `controller/LibroController.py` — lógica de creación, edición, borrado y listado de libros.
- `controller/FileController.py` — persistencia de los libros en `saves/librosSaved.txt`.

## Funcionalidades del menú

1. Crear libro
2. Eliminar libro
3. Editar libro
4. Mostrar todos los libros
5. Guardar libros
6. Salir

Al iniciar, el programa recupera automáticamente los libros guardados en `saves/librosSaved.txt`.

## Cómo ejecutarlo

```
python main.py
```
