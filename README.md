# "TRIPTICO"
* [Link del problema](https://lms.laboratoria.la/cohorts/cdmx-2017-10-bc-core-am/courses/interactive-site/00-html-and-css/10-guided-exercises)

## Apuntes de how to solve it
* Creacion de CSS de:

    * Parrafos de cada tercios del triptico
    * Una para el titulo
    * Uno para el parrafo
    * Aqui usaras tmb el inline.block

### Imágenes:
* Sera la ultima linea de tu bloque de HTML de cada tercio de triptico.
* Para alinear en cada cara del trptico, usas display inline-block y margen (0, auto)
* Margen a las imagenes.

## OPCIONES DE COMO RESOLVER PONER LAS 3 CAJAS PRINCIPALES:
* Se pueden utilizar:
    ```
    * Display (Inline -block)
    * Position
    * Floats
    ```
* ¿Por qué no Position?
    ```
    * Es muy inexacto en cuanto a medidas.
    * Es mucho trabajo, ya que deberas hacer mas calculos acerca de los px que deberas de mover y acomodar para los 3 bloques.
    ```
* ¿Por qué no floats?
    ```
    * Por que requiere el Clear Float, lo cual implica mas trabajo porque es limpiar uno por uno de los floats(bloques).
        ```

* ¿Por qué SI inline-block?
    ```
    * Es mas fácil de manejar, los bloques se acomodan automaticamente y solo debes de definir los paddings, margin y widths del triptico.
    ```
