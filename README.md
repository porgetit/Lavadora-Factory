# Lavadora - Proyecto de Fábrica de Lavadoras en Java

## Descripción del Proyecto

Este proyecto implementa un sistema básico que simula una fábrica de lavadoras. El objetivo principal es explorar las capacidades del patrón de diseño Factory. La fábrica, representada por la clase `Ensambladora`, tiene la capacidad de construir lavadoras de diferentes marcas según la indicación proporcionada. Cada marca de lavadora es una subclase de la clase abstracta `lavadoras`.

## Estructura del Proyecto

El proyecto consta de siete archivos en Java:

1. **Ensambladora.java**
   - Implementa la interfaz `Ensamblar` y contiene la lógica de la fábrica para construir lavadoras de distintas marcas.

2. **Ensamblar.java**
   - Una interfaz que declara el método `toBuild`, utilizado por la clase `Ensambladora` para construir lavadoras.

3. **Lavadora.java**
   - El punto de entrada principal que crea una instancia de la `Ensambladora` y construye lavadoras de diferentes marcas.

4. **Marca1.java**
   - Subclase de `lavadoras` que representa una lavadora de la Marca 1.

5. **Marca2.java**
   - Subclase de `lavadoras` que representa una lavadora de la Marca 2.

6. **Marca3.java**
   - Subclase de `lavadoras` que representa una lavadora de la Marca 3.

7. **lavadoras.java**
   - Clase abstracta que sirve como base para las diferentes marcas de lavadoras.

## Instrucciones de Uso

1. **Creación de Lavadoras**
   - El archivo `Lavadora.java` contiene el método `main` que demuestra la creación de lavadoras de diferentes marcas utilizando la fábrica.

2. **Marcas de Lavadoras**
   - Cada marca de lavadora (Marca 1, Marca 2, Marca 3) extiende la clase abstracta `lavadoras` y proporciona su propia implementación del método `getDescription`.

## Consideraciones Importantes

- **Patrón de Diseño Factory:** El proyecto utiliza el patrón de diseño Factory para permitir la creación de objetos (`lavadoras`) de manera centralizada.

- **Polimorfismo:** La utilización del polimorfismo permite que las diferentes marcas de lavadoras compartan una interfaz común y se utilicen de manera intercambiable.

- **Abstracción:** La clase abstracta `lavadoras` proporciona una abstracción común para todas las marcas, permitiendo un diseño más flexible y escalable.

¡Explora y disfruta del proceso de construcción de lavadoras en esta fábrica básica implementada en Java! Si tienes alguna pregunta o sugerencia, no dudes en contactar al autor.
