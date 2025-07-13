# HTML
## Que es HTML
- El **creador** de hmtl fue **Tim Berners-Lee**
- HTML es un lenguaje, pero no es un lenguaje de progamación.

- HTML fue **creada en 1991**.

- HTML significa HyperText Markup Language (Lenguaje de Marcado de Hipertexto).

- HTML define la estructura básica de una página web.
- Modifica de arriba hacia abajo.

## Etiquetas 
En las etiquetas tiene jerarquia tiene su orden.
1. < !DOCTYPE html > **-->**
2. < html > **-->** 
3. < head > **-->** **Encabezado** 
    - < meta charset="UTF-8" >
    - < TItle > < /TItle >
- < /head >

4. < body > **-->** **Cuerpo**
    - < style > < /style > --> **Estilos**
    - < h > < /h > **-->** **Titulo**
        - Para colocar el titulo
        - Los niveles de h estan del 1 al 6
    - < p > < /p > **-->** **Parrafo**
        - Para poner el contenido
    - < ul > < /ul > **-->** **Lista desordenadas**
        - < li > < /li > **-->** se utiliza para definir un elemento de lista

        Ejemplo:

            - hola
    - < ol > < /ol > **-->** **Lista Ordenadas**
        - < li > < /li > **-->** se utiliza para definir un elemento de lista

        Ejemplo:

            1. hola
            2. como estan
            3. mama huevo
    - < strong > < /strong > y < b > < /b > **-->** **Negrilla**

        Ejempolo: 
        
            <b>hola</b>
            
    
    - < br > **-->** **Salto de linea**
        ejemplo:
            

    - < mark > < /mark > **-->** **Resaltador**
    - < s > < /s > **-->** **Tachado**
    - < em > < /em > **-->** **Cursiva**
    - < small > < /small > **Letra chica**

    - < table > **-->** **Tabla**
        - < caption > < /caption > **-->** Sirve para dar titulo o encabezado a la table
        - < thead > **-->** Cabeza de tabla
            - Significa cabeza de tabla.
            - Se usa para definir la fila o filas de encabezado de la tabla.
            - Normalmente contiene etiquetas < th >, que son celdas de encabezado.

          < /thead > 

        - < tbody > **-->** Cuerpo de Tabla
            - Significa cuerpo de tabla.
            - Contiene el contenido principal de la tabla.
            - Dentro van las filas < tr >, y dentro de cada fila, las celdas < td >.

          < /tbody >
        - < tfoot > **-->** Pie de Tabla
            - Significa pie de tabla 
            - lleva resumenes, conclucion o informacion adicional
            - Notmalmente contiene etiquetetas < tr >, y dentro las etiquetas < td >.
          < /tfoot >

        - < th > < /th> **-->** **Encabezado en uns tabla**
        - < td > < /td> **-->** **Celda de datos dentro de una tabla**
        - < table border="1"> **-->** **Añadir marco** funcion antigua
    - /table >
    - < a href="" > < /a > **-->** **se utiliza para crear enlaces o hipervínculos**
    < /body >


## Estructura inicial e Ensecial del HTML.

1. < !DOCTYPE html >
2. < html lang="en" >
3. < head >
    - < meta charset="UTF-8" >
    - < meta name="viewport" content="width=device-width, initial-scale=1.0" >
    - < title >Document< /title >
-  < /head >
5. < body >
    
- < /body >
- < /html >