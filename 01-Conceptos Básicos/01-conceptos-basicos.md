# Conceptos Básicos

## Variables

JavaScript proporciona siete tipos de datos diferentes que son `undefined`, `null`, `boolean`, `string`, `symbol`, `number`, y `object`.

Las computadoras distinguen entre números, como el número `12`, y cadenas, como `"12"`, `"perro"` o `"123 gatos"`, que son colecciones de caracteres. Las computadoras pueden realizar operaciones matemáticas en un número, pero no en una cadena.

Las `variables` permiten a las computadoras almacenar y manipular datos de forma dinámica. Lo hacen mediante el uso de una "etiqueta" para señalar los datos en lugar de utilizar los datos en sí. Cualquiera de los siete tipos de datos que mencionamos puede almacenarse en una variable.

Las `variables` son similares a la representación de un punto en corrdenadas x e y, que usa en matemáticas, lo que significa que son un nombre simple para representar los datos a los que queremos referirnos.

Le podemos decir a JavaScript que cree o declare una variable colocando la palabra clave `var` delante de ella, así:

``` JavaScript
var miNombre;
```

Hemos creado una variable llamada `nombre`. En JavaScript terminamos las declaraciones con punto y coma (no es obligatorio, pero si recomendable). Los nombres de las variables pueden estar formados por números, letras y `$` o `_`, pero no pueden contener espacios ni comenzar con un número.

## Asignar valores

En JavaScript, puede almacenar un valor en una `variable` con el [Operador de Asignación](https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Operadores/Assignment_Operators).

```JavaScript
var miNombre;
miNombre = 'Juan';

var tuNombre;
tuNombre = 'Pedro';
```

Tambien es posible hacer la declaración de la variable y la asignación de un valor en una misma línea:

```JavaScript
var universidad = 'Universidad de Piura';
```