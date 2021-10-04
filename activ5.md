# Actividad 5
##    ***JSON y XML***
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRW2FknHTwol_TJEscxYeYzaHoPksL01YJMcA&usqp=CAU)
### ¿Qué es JSON?
> JavaScript Object Notation (JSON)
>Es un formato ligero de intercambio de datos. JSON es de fácil lectura y escritura para los usuarios. JSON es fácil de analizar y generar por parte de las máquinas. JSON se basa en un subconjunto del lenguaje de programación JavaScript
>En JSON existen dos tipos de elementos:
1. Un objeto es un conjunto desordenado de pares nombre/valor. Un objeto comienza con {llave de apertura y termine con }llave de cierre. Cada nombre es seguido por :dos puntos y los pares nombre/valor están separados por ,coma.
![](https://www.json.org/img/object.png)
2. Un arreglo es una colección de valores. Un arreglo comienza con [corchete izquierdo y termina con ]corchete derecho. Los valores se separan por ,coma.
![](https://www.json.org/img/array.png)
**EJEMPLO**
Archivo colores1.json	
{
    "arrayColores":[{
            "nombreColor":"rojo",
            "valorHexadec":"#f00"
        },
        {
            "nombreColor":"verde",
            "valorHexadec":"#0f0"
        },
        {
            "nombreColor":"azul",
            "valorHexadec":"#00f"
        },
        {
            "nombreColor":"cyan",
            "valorHexadec":"#0ff"
        },
        {
            "nombreColor":"magenta",
            "valorHexadec":"#f0f"
        },
        {
            "nombreColor":"amarillo",
            "valorHexadec":"#ff0"
        },
        {
            "nombreColor":"negro",
            "valorHexadec":"#000"
        }
    ]
}

### ¿Qué es XML?
>Siglas en inglés de eXtensible Markup Language, traducido como 'Lenguaje de Marcado Extensible' o 'Lenguaje de Marcas Extensible', es un metalenguaje que permite definir lenguajes de marcas desarrollado por el World Wide Web Consortium (W3C) utilizado para almacenar datos en forma legible.

>XML es un lenguaje de marcado similar a HTML. Esto significa que, a diferencia de otros lenguajes de marcado, XML no está predefinido, por lo que debes definir tus propias etiquetas. El propósito principal del lenguaje es compartir datos a través de diferentes sistemas, como Internet.

>Hay muchos lenguajes basados en XML; Algunos ejemplos son XHTML, MathML, SVG, XUL, XBL, RSS, y RDF. También puedes crear uno propio.
>Cinco  caracteres importantes:

| Entidad    | Caracter   | Descripción  | 
| ---------- | ---------- |--------------|
| &lt;       |    <       | Menor que    |
| &gt;       |    >       | Mayor que    |
| &amp;      |    &       | Ampersand    |
| &quot;     |    "       | Comilla doble|
| &apos;     |    '       | Apóstrofe    |

**EJEMPLO**
<?xml version="1.0" encoding="UTF-8"?>
<note>
  <to>Tove</to>
  <from>Jani</from>
  <heading>Reminder</heading>
  <body>Don't forget me this weekend!</body>
</note>

##### Referencias
1. [Formato JSON (JavaScript Object Notation)](https://www.ibm.com/docs/es/baw/20.x?topic=formats-javascript-object-notation-json-format)
2. [Introducción a JSON](https://www.json.org/json-es.html)
3. [Aprender a programar](https://www.aprenderaprogramar.com/index.php?option=com_content&view=article&id=957:ejemplos-json-archivo-datos-cambio-formato-convertidor-on-line-xml-a-json-y-al-reves-minificar-cu01214f&catid=83&Itemid=212)
4. [Introducción a XML](https://developer.mozilla.org/es/docs/Web/XML/XML_introduction)
5. [Ejemplo xml](https://www.w3schools.com/xml/)