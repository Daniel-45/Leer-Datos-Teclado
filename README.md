# Librería

En este repositorio hay una librería para leer los datos por teclado.
  
El motivo de utilizar esta librería para leer los datos por teclado es porque en ocasiones la clase ***Scanner*** no funciona correctamente y hay que limpiar el buffer.

## Eclipse IDE

Utilizar librería:

1. Añadir la librería al build path
- Botón derecho sobre el poyecto
- Seleccionar Build Path y Configure Build Path
- En la pestaña Libraries, seleccionar ClassPath y la opción Add External JARs
- Buscar el directorio donde está la librería **daw.jar** y añadir a ClassPath

## Build Path

!["](/files/build-path.png)

2. Ejemplo de uso

```
String nombre;
nombre = Teclado.leerString("\nIntroduzca su nombre:");
```