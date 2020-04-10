# Conceptos Básicos

## Variables

Las `variables` permiten a las computadoras almacenar y manipular datos de forma dinámica. Lo hacen mediante el uso de una "etiqueta" para señalar los datos en lugar de utilizar los datos en sí. 

Las `variables` son similares a la representación de un punto en corrdenadas x e y, que usa en matemáticas, lo que significa que son un nombre simple para representar los datos a los que queremos referirnos.

Le podemos decir a JavaScript que cree o declare una variable colocando la palabra clave `var` delante de ella, así:

``` JavaScript
var miNombre;
```

Hemos creado una variable llamada `nombre`. En JavaScript terminamos las declaraciones con punto y coma (no es obligatorio, pero si recomendable). Los nombres de las variables pueden estar formados por números, letras y `$` o `_`, pero no pueden contener espacios ni comenzar con un número. 

Las variables en javascript son sensibles a mayúscular y minúsculas ( [Case Sensitivity](https://es.wikipedia.org/wiki/Sensible_a_may%C3%BAsculas_y_min%C3%BAsculas)). Es diferente la variable `miNombre` a `minombre` y a `MINOMBRE`.

> Buenas prácticas:  
> En javascript se suele usar el estilo `camelCase` para nombrar una variable, 
> la primera palabra se escribe en minúscula y las demás solo la primera letra en mayúscula.

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
var ciclo = 6;
```

Hemos visto que podemos almacenar un texto `'Universidad de Piura'` y también un número `6`, estos dos diferentes `tipos de datos` que podemos usar. JavaScript proporciona siete tipos de datos diferentes que son `string`, `number`, `undefined`, `null`, `boolean`, `symbol`, y `object`.

Cuando se declaran las variables en JavaScript, tienen un valor inicial de `undefined`. Si realiza una operación matemática en una variable no definida, su resultado será `NaN`, que significa *"Not a Number"*. Si concatena una cadena de texto con una variable no definida, obtendrá una cadena literal de `"undefined"`.

```JavaScript
var nombre;
var edad;

"mi nombre es" + nombre; // Muestra: "Mi nombre es undefined"
edad + 1;  // Muestra: NaN

nombre = 'Juan Pérez';
edad = 22;

"mi nombre es" + nombre; // Muestra: "Mi nombre es Juan Pérez"
edad + 1;  // Muestra: 23
```

