# Juego de la vida

## Breve descripción de la aplicación

* Resumen: el software que se publica en este repositorio permite
  [El Juego de la vida](https://www.youtube.com/watch?v=ouipbDkwHWA)
* Versión: 1.0.

## Compilación del programa

Se ha incluido un `makefile` que define, entre otras tareas, la
generación de un `.jar`:

```console
make jar
```

## Cómo generar el HTML a partir del Javadoc

El HTML con los comentarios se puede obtener mediante la siguiente
sentencia:

```console
make html
```
## Cómo ejecutar el programa con make

```console
make jugar
```


## Estructura del código

Tal y como muestra la siguiente figura
![diagrama UML](https://user-images.githubusercontent.com/115775737/222677046-f9561ac8-a0fe-46c8-aa01-add740ab3e62.png)

existen dos clases: `Tablero.java`, en el paquete `dominio`, que
contiene el método que realiza la simulación; y `Principal.java`, en el
paquete `principal`, que invoca el método de simulación.

