# Past Simple vs Past Continuous

Práctica digital de *past simple vs past continuous* para 5th form: 8 hojas de
ejercicios (una por PDF), con corrección automática y envío del resultado a la
docente por mail.

**Sitio:** https://mecidan-design.github.io/Past-simple-vs-past-continuous/

## Qué hay

Un solo archivo, `index.html`, con un menú y 8 sub páginas (se navega por
`#1` … `#8`). Cada hoja conserva la estructura de su PDF: títulos, consignas,
numeración, cajas de gramática, bancos de palabras y la tabla de dos columnas.
El texto de los ejercicios está copiado literal de los PDF.

| Hoja | Contenido |
|---|---|
| 1 | Past continuous or past simple: opciones + verbos entre paréntesis |
| 2 | Past simple / past continuous: 10 oraciones |
| 3 | Past simple vs. past continuous: 25 oraciones + las dos cajas |
| 4 | La tabla Past simple / Past continuous: 15 + 15 |
| 5 | Review test 2: partes A, B, C y D |
| 6 | Past continuous vs simple past: 4 partes, con ejemplos resueltos |
| 7 | Dos cajas + dos bancos de palabras |
| 8 | YouTube, Captain Cook, when / while |

## Cómo está hecho

Un archivo, sin dependencias, **abre sin internet**. Vanilla JS, fuentes de
sistema y **sin sonido de ninguna clase**. Bloques `<script>` separados a
propósito: `data-block` (solo contenido), `logic-block` (funciones puras),
`report-block` (envío de resultados) y `engine-block` (el motor).

## Envío de resultados

Al pie de cada hoja hay una tarjeta con nombre, curso y docente. El botón manda
una fila a la planilla y un mail a la docente elegida, con el puntaje y la lista
de lo que el alumno escribió mal junto a la respuesta correcta. El menú puede
mandar el acumulado de todas las hojas hechas en esa computadora.

> Esto no es una nota de examen: todo ocurre en la máquina del alumno. Sirve
> como registro de trabajo y para ver dónde se traba el curso.

© Prof Dan M. Mecikovsky
