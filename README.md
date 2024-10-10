# Actividad 5 Sobre XML

## 1. Indica las características propias del lenguaje XML.

XML (Extensible Markup Language) es un lenguaje utilizado principalmente para almacenar y transportar datos de manera estructurada.Entre sus características propias incluyen:

- Estructura jerárquica
- Etiquetas personalizadas
- Legibilidad humana
- Bien formado
- Portabilidad
- Soporte de esquemas
- Sensible a mayúsculas y minúsculas
- Soporte para Unicode
- Uso de namespaces

## 2. Identifica la estructura de un documento XML y sus reglas sintácticas.

Un documento XML (Extensible Markup Language) tiene una estructura bien definida que sigue un conjunto de reglas sintácticas. Estas reglas aseguran que el documento sea legible tanto para humanos como para máquinas.

A continuación, se detallan los principales componentes y reglas de un documento XML:

## Estructura básica de un documento XML
- **Declaración XML (opcional pero recomendada):**

    - Es la primera línea del documento y declara que es un documento XML. Puede especificar la versión y el conjunto de caracteres (codificación).
- **Elemento raíz:**

    - Todo documento XML debe tener un único elemento raíz que contenga todos los demás elementos. Este elemento actúa como el contenedor principal de todo el contenido del XML.
- **Elementos:**

    - Los elementos son las etiquetas que forman el contenido del XML. Cada elemento debe tener una etiqueta de apertura y una de cierre. Los elementos pueden anidarse.
- **Atributos:**

    - Los elementos pueden tener atributos que proporcionan información adicional sobre el elemento. Estos atributos se colocan dentro de la etiqueta de apertura.
- **Contenido:**

    - Los elementos pueden contener texto, otros elementos (anidados), o pueden estar vacíos.
- Comentarios:

    - Los comentarios en XML comienzan con < !-- y terminan con -- >. No se procesan como parte del contenido del documento.

## Reglas sintácticas del XML

- Todo documento debe tener un único elemento raíz.
- Las etiquetas deben abrirse y cerrarse correctamente.
- Los elementos pueden tener atributos.
- Los atributos deben estar entre comillas.
- El XML distingue entre mayúsculas y minúsculas.
- Deben escaparse los caracteres especiales dentro del contenido del documento.

## 3. En XML qué es un nodo raíz.

Un nodo raíz es el nodo principal o de nivel más alto en un documento XML. Es el contenedor que engloba todos los demás elementos y, por lo tanto, solo puede haber un nodo raíz en un documento XML.

## 4. Indica qué es un elemento vacío. Ejemplos

Un elemento vacío o conjunto vacío en matemáticas y en programación se refiere a un conjunto o estructura que no contiene ningún elemento.

**Ejemplos:**

- Lista vacía en Python
```
lista_vacia = []
```
- Cadena vacía en JavaScript
```
let cadenaVacia = "";
```
- Arreglo vacío en Java
```
int[] arregloVacio = new int[0];
```
## 5. Qué sentido tiene crear documentos XML bien formado.

Crear documentos XML bien formados tiene varios propósitos y ventajas:

- Interoperabilidad entre sistemas
- Estructura y jerarquía de datos
- Validación
-  Procesamiento eficiente

Estas son una de las ventajas que tienen.

## 6. Qué es un espacio de nombres. Ventajas de uso.

Un espacio de nombres (o namespace en inglés) es un contenedor que permite agrupar identificadores (como variables, funciones, clases) para evitar colisiones de nombres dentro de un programa. Aqui algunas ventajas:

- Evitar colisiones de nombres
- Mejora la organización
- Claridad en el código
- Mantenibilidad y escalabilidad
- Reutilización de código

## 7. Entidades en XML. Crea un XML con las entidades vistas en clase.

Las entidades son un mecanismo que permite definir abreviaturas para cadenas de texto o para caracteres especiales que no se pueden utilizar directamente en el documento XML. Algunas entidades son <, >.
```
<ciudad cod="1">
    <nombre>Tokyo</nombre>
    <pais continente="Asia">Japon</pais>
    <poblacion>37.115.035</poblacion>
    <fundacion>Año 1457 d.C.</fundacion>
      <descripcion>Es conocida por su mezcla única de modernidad y tradición, con rascacielos futuristas, tecnología avanzada, y una rica herencia cultural que incluye templos, santuarios y jardines históricos. </descripcion>
</ciudad>
```

## 8. Comentarios en XML. Muestra uno de los ejercicios anteriores con el enunciado dentro de un comentario. Dentro del comentario deben aparecer dos guiones.

los comentarios permiten incluir anotaciones o explicaciones que no serán procesadas por el parser ni aparecerán en la salida final del documento. Estos comentarios pueden ser útiles para documentar el código.

```
<!-- Este es un comentario que no será procesado -->
<ciudades>
    <nombre>Tokyo</nombre>
<ciudades>
```