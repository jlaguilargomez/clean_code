# Curso

[Course](https://indra.udemy.com/course/writing-clean-code/learn/lecture/23110862#overview)

[Notion](https://www.notion.so/jlaguilargomezdevelop/Clean-Code-9ea680d7a42c4d5280f83bcb0c5acdf4)

---

# Introducción

Escribir código limpio es fundamental para el mantenimiento y mejora de nuestras aplicaciones en un futuro. Para otras personas o para nosotros mismos el día de mañana. Asegura su legibilidad y entenidmiento.

Un par de ejemplos:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d2e87f10-d354-4684-b9be-c0b3387baf6d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d2e87f10-d354-4684-b9be-c0b3387baf6d/Untitled.png)

No se puede decir que la función `processTransactions()` sea un ejemplo de "Clean Code" por la complejidad de esta y los elementos anidados que contiene.

Se comenta en el vídeo que la siguiente pieza de código, escrita en Python, tampoco es un ejemplo perfecto de "**Clean Code**", ya que implica darle más de un par de vueltas a ver qué es lo que hace exactamente  🧙🏿‍♂️ *[no creo que sea tan complejo...]*:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5ecd3394-b604-4abe-a2ff-0a84e420e1ec/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5ecd3394-b604-4abe-a2ff-0a84e420e1ec/Untitled.png)

> *"Clean code" es un concepto que define la facilidad de entender cómo funciona una pieza de código, más que si funciona o no (que se dá por hecho)*

Veamos el ejemplo de antes, reconvertido con las buenas prácticas del **Clean code.**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1d4fa7a1-d302-45e4-a55d-6ba764ec1533/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1d4fa7a1-d302-45e4-a55d-6ba764ec1533/Untitled.png)

*🧙🏿‍♂️ [¡DPM!, esto se entiende bastante mejor, y eso que sólo han cambiado los nombres!]*

Resumiendo... **¿Qué es el Clean Code?**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d7e814f6-cdd8-45c3-9d1c-b30bf0a30f8a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d7e814f6-cdd8-45c3-9d1c-b30bf0a30f8a/Untitled.png)

**Tienes que ver el hecho de escribir código como si estuvieras contando una historia. No es ridículo, de verdad, dicen que funciona y puede ayudar mucho a poner en marcha buenas prácticas. Tómalo como si fuera un ensayo del que TÚ eres el autor.**

Los conceptos fundamentales que hay que tener en cuenta a la hora de escribir Clean Code son los siguientes:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a20fefa7-8943-4411-951f-4f882f5ccd56/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a20fefa7-8943-4411-951f-4f882f5ccd56/Untitled.png)

Los conceptos que vamos a ver son aplicables a cualquier lenguaje de programación, no sólo a Python o JS, que son los lenguajes que usaremos a lo largo del curso.

> *Clean Code doesn't require strong typing*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9cf2d182-8c72-4d1e-8492-d45ca3604658/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9cf2d182-8c72-4d1e-8492-d45ca3604658/Untitled.png)

Se hace mucho incapié en el hecho de que escribir "clean code" es independiente del lenguaje o paradigma de programación que estemos usando. Los conceptos son universales y deben de ser aplicables a cualquier "estilo" de programación:

*No matter which programming language or style you're using ...*

- ... *you still want readable and meaningful names*
- *... you still want slim, concise functions or methods*
- *... you still want understandable code flow*

**MUY IMPORTANTE: ideas fundamentales para diferenciar el CLEAN CODE de otros conceptos conocidos**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3dde9f29-b931-4962-acd7-6c0749df66c3/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3dde9f29-b931-4962-acd7-6c0749df66c3/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9cbb79c8-4c74-4b26-90a5-20b53d25dfeb/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9cbb79c8-4c74-4b26-90a5-20b53d25dfeb/Untitled.png)

**Escribir "Clean Code" es un proceso continuo que NUNCA alcancará su máximo, por lo que es clave la refactorización de código cuando estamos atendiendo a nuevas funcionalidades. Pero OJO, tampoco hay que obsersionarse si eso va a impedir el avance. Como siempre: equilibrio.**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/923aea6e-4d60-460d-ae6e-37860da201eb/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/923aea6e-4d60-460d-ae6e-37860da201eb/Untitled.png)

Este es un concepto clave que nos puede ayudar mucho en el día a día:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/93833ee1-e8cb-4ab0-b304-a1bf5465eab6/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/93833ee1-e8cb-4ab0-b304-a1bf5465eab6/Untitled.png)

Escribir Clean code desde el inicio, es una inversión asegurada de cara al día de mañana (🧙🏿‍♂️ *¡curratelo más hoy para poder tomartelo con más calma en el futuro!)*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/865f0dd4-1cc6-46ea-9d77-a9f7f0ea5e24/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/865f0dd4-1cc6-46ea-9d77-a9f7f0ea5e24/Untitled.png)

---

# Naming

> *Names should be "meaningful"*

Tenemos que tener claro qué hace cada variable, función, objeto o clase prácticamente por su nombre. Veamos dos ejemplos contrapuestos:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/75c46bd7-3462-405b-8c43-3c238cda5c57/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/75c46bd7-3462-405b-8c43-3c238cda5c57/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/61793945-6cae-4daf-8623-202cedfee7b1/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/61793945-6cae-4daf-8623-202cedfee7b1/Untitled.png)

Evidentemente esto es muy subjetivo, pero hay **"constantes" que deberían ser siempre respetadas:**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0a9de463-6d70-45a5-8340-4dd3b37fdc9e/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0a9de463-6d70-45a5-8340-4dd3b37fdc9e/Untitled.png)

## Name Casing

Como sabemos, existen diferentes "notaciones" para escribir los nombres, que dependen del tipo de elemento (variable, función, objeto.... ) y del lenguaje de programación utilizado:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d4078b15-eba6-456d-9137-2530f1c8aa5b/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d4078b15-eba6-456d-9137-2530f1c8aa5b/Untitled.png)

## Naming variables, constants & properties

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c16fd0ff-c6ee-4458-9b05-b4da3ba4293a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c16fd0ff-c6ee-4458-9b05-b4da3ba4293a/Untitled.png)

**Para almacener BOOLEANS, es recomendable siempre usar "preguntas" cerradas, es decir, nombres que requieran de respuesta TRUE / FALSE. Por ejemplo:** `isActive` ó `loggedIn`

Unos ejemplos de nombres acertados o no tan acertados:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0fed5646-3249-4b70-b89f-1d0ecfa897ab/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0fed5646-3249-4b70-b89f-1d0ecfa897ab/Untitled.png)

## Naming functions & methods

Para funciones y métodos, como sabemos son acciones, por lo que deben "describir" la acción a realizar. En el caso de que nos vayan a devolver un BOOLEAN, podemos usar una notación similar a la que usabamos en el caso de variables: `isLoggedIn()` `customer.userIsValid()`

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7f34cbfc-3a44-417a-b1ab-22956396e75e/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7f34cbfc-3a44-417a-b1ab-22956396e75e/Untitled.png)

Ejemplos sobre este caso:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d4868b5f-11a3-453c-9ba0-87f6c0952fdb/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d4868b5f-11a3-453c-9ba0-87f6c0952fdb/Untitled.png)

## Naming classes

Los nombres de las clases deben dejar claro el objeto que van a instanciar: `User, Product, Customer, Course`

Veamos ejemplos ahora de buenos nombres:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/552ee35e-f482-4498-9d9a-46c49229d527/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/552ee35e-f482-4498-9d9a-46c49229d527/Untitled.png)

**Evidentemente, trabajando con librerías externas tenemos que adaptarnos a los métodos que nos da, y no podemos "mejorar" el código de estas. Por lo que deberemos adaptarnos a lo que tenemos y hacer que, mediante el código que escribimos nosotros, se entienda lo que estamos obteniendo de estas librerías externas.**

## Common errors and pitfalls

No es necesario crear nombres en los que la información  es redundante o carece de valor adicional:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b1c7ca0b-2550-4c12-b2e1-5fa5af0a2311/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b1c7ca0b-2550-4c12-b2e1-5fa5af0a2311/Untitled.png)

Parece una tontería, pero no tiene sentido llamarlo `userWithNameAndAge` porque se da por hecho que un usuario debería tener NOMBRE y EDAD. ¿Si tuviera más valores los reflejaríamos todos en el nombre?

Evita "slangs", abreviaciones que no estén del todo claras y desinformación:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/30b9e7be-763d-4982-9889-7ff55b4adba4/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/30b9e7be-763d-4982-9889-7ff55b4adba4/Untitled.png)

Elige nombres descriptivos y **distintivos** , que no se confundan con otros similares que ya existan:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/17dbdb0d-819c-4695-9462-cd85c2504fde/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/17dbdb0d-819c-4695-9462-cd85c2504fde/Untitled.png)

Se consistente a la hora de elegir los nombres que vas a utilizar. **Si eliges un patrón, ve con él hasta el final.**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d3cb8f1c-3d0f-4018-be44-a344398cfa50/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d3cb8f1c-3d0f-4018-be44-a344398cfa50/Untitled.png)

En el ejercicio final del curso, se muestra una corrección de los nombres de una clase con diferentes métodos internos.  En Python. Se entiende bien.

### Resumen del módulo

[Naming-Summary.pdf](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c725d79b-62f3-43be-9b2b-1e4f36aaf9b8/Naming-Summary.pdf)

---

# Code structure, comments & formatting

## Comments

Los comentarios se deben usar en su justa medida, ya que el código debería ser lo suficientemente explicativo como para que no hicieran falta. 

Sólo se debiera usar comentarios en aquellas circunstancias en las que sea muy necesario comentar alguna funcionalidad que no queda clara en el código.

**Entre otros comentarios no recomendados, se ha referencia a los que suelo utilizar para separar partes del código** `// ****`

Vamos a ver unos ejemplos de "comentarios de mierda":

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/81c315c8-a6b2-4e07-9ffd-cfca590525c0/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/81c315c8-a6b2-4e07-9ffd-cfca590525c0/Untitled.png)

En contraposición con esto, se enumeran unas causas en las que los comentar el código se hace bastante necesario / útil:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b5b2e9d5-77d5-45d6-8c83-f6590f7b58ba/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b5b2e9d5-77d5-45d6-8c83-f6590f7b58ba/Untitled.png)

**Como norma, evita los comentarios a menos que sea neceario**

## Code formatting

Se diferencias dos tipos principales de formato de código:

- Formato vertical: espacio entre líneas, agrupamiento de código ...
- Formato horizontal: identación, longitud de líneas ...

**CLAVE: la guía de estilo de airbnb, es una biblia para JavaScript**

[airbnb/javascript](https://github.com/airbnb/javascript#types)

### Vertical formatting

No hay una regla estricta sobre la longitud de los archivos, pero hay conceptos fundamentales que se deben tener en cuenta:

- Si hay más de una clase... lo habitual es que haya más de un  archivo
- Cada archivo debería responder a una lógica o concepto claro

Los conceptos diferenciados deberían separarse mediante *break lines:*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a2a3c9cf-48ff-4b56-81c4-28f28a868ed1/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a2a3c9cf-48ff-4b56-81c4-28f28a868ed1/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4c72c750-5690-406e-9e72-491005d74fa8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4c72c750-5690-406e-9e72-491005d74fa8/Untitled.png)

Se nota la diferencia ... *🧙🏾‍♂️ [Por suerte esto lo suelo tener bastante en cuenta]*

Mantén funcionalidades y métodos dependientes, en posiciones cercanas dentro del código. Que no haya que estar buscándolo por todo el archivo ....

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/748c1747-cfa2-4468-b077-5fa57fff78a5/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/748c1747-cfa2-4468-b077-5fa57fff78a5/Untitled.png)

### Horizontal formatting

Conceptos obvios. Muchos de ellos se resuelven con una correcta configuración del archivo de "prettierrc", por ejemplo.

Intenta utilizar, en la medida de lo posible, líneas que no sobrepasen la pantalla, nombres no demasiado largos y parámetros concisos (?).

**Como nota adicional, ¡no hagas operaciones en los argumentos de las funciones!, es mejor que crees una variable nueva, te encargues de operar y luego ya la pases como argumento.**

### Resumen del módulo

[Comments-Formatting-Summary.pdf](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/58132126-18fa-4e09-b20a-2920ff5201f0/Comments-Formatting-Summary.pdf)

---

# Functions & Methods

> *Be concise - In every aspect*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e4c2ff9c-f3fa-4c0d-bb93-c429b770798f/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e4c2ff9c-f3fa-4c0d-bb93-c429b770798f/Untitled.png)

Una regla muy importantes es: **minimizar el número de parámetros que acepta la función.** Como norma se suele establecer que **lo suyo es recibir 1-2 argumentos**.

Vamos a ver un ejemplo de lo que significa introducir N argumentos en una función:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f84f09c6-2828-4ce5-b14d-852616bdcef8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f84f09c6-2828-4ce5-b14d-852616bdcef8/Untitled.png)

Como se puede observar, lo recomendable es ≤ 2 argumentos, intentando evitar siempre que sea posible las de 3+, ya que se pueden reducir mediante otras técnicas: *closures,* funciones específicas, argumentos tipo objetos ...

**La clave está en MINIMIZAR el número de parámetros, salvo que sea lo suficientemente comprensible como para aceptar más (en circunstancias muy concretas)**

Un ejemplo de una clase que, en origen, aceptaba 3 parámetros, refactorizada:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fbd304a5-066a-40c1-a6aa-5b8261d3558a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fbd304a5-066a-40c1-a6aa-5b8261d3558a/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5b292e79-1935-4af9-97d1-c36a91a6d56e/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5b292e79-1935-4af9-97d1-c36a91a6d56e/Untitled.png)

Hemos pasado de aceptar 3 parámetros a 1 sólo, que es el OBJETO que contiene los datos del usuario. 

Con **Typescript**, podemos mejorar aún más este código tipando el argumento que va a recibir por parámetro: `{name: string, age: number, email: string}` 

Otro ejemplo de una función que, en origen, aceptaba 3 parámetros: 2 operandos y el operador que realiza la acción:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c6d37610-8d92-4970-a9d2-21a49f5cbd44/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c6d37610-8d92-4970-a9d2-21a49f5cbd44/Untitled.png)

De esta forma pasamos un **OBJETO** o un **MAP** que ayuda a conocer qué datos se le está pasando en cada caso.

Internamente "**destructuramos**" y procedemos a hacer lo que toque hacer.

## Funciones con número variable de parámetros

En algunos casos nos encontramos con funciones que reciben un número variable de parámetros, pongamos por caso:

```jsx
function sumUp(...numbers){
	let sum = 0;
	for (const num of numbers){
		sum += num;
	}
	return sum;
}

const total = sumUp(1,5,7,-8,10);
```

Vale, podríamos pasar un ARRAY como único argumento que contuviera todos estos números, pero vamos a darle una vuelta.

Realmente estamos pasando 1 sólo argumento en la función `...numbers`, desde un punto de vista estricto no, pero sí que se considera como un array de datos. En todo existen excepciones, y esta es una excepción a la regla que hemos establecido.

**La clave del CLEAN CODE es que sea fácil de entender y manejar, y este caso es perfectamente comprensible.**

## Output parameters

Tenemos que tener especial cuidado con la manipulación de parámetros internos del argumento que pasamos a la función:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/57e4d9a2-9785-40ca-948c-59bd990db4c1/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/57e4d9a2-9785-40ca-948c-59bd990db4c1/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ee7c757a-bf42-4ea6-9b60-637e5b178513/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ee7c757a-bf42-4ea6-9b60-637e5b178513/Untitled.png)

Aunque los dos casos parezcan similares, en el segundo estamos indicando con el NOMBRE de la función, que le estamos añadiendo un parámetro ID.

Pero sería más claro aún si tenemos en cuenta un punto de vista OOP:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/27d29cdc-db0d-4b56-9c36-309165dadacd/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/27d29cdc-db0d-4b56-9c36-309165dadacd/Untitled.png)

Crear un método del objeto `user`que añada el identificador del usuario.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/53824b98-5757-480d-9591-1faf1ff9cff8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/53824b98-5757-480d-9591-1faf1ff9cff8/Untitled.png)

**Esto que acabamos de ver es CLAVE en la programación funcional, ya que estamos intentando EVITAR la modificación de los argumentos que se le pasan a la función (FUNCIONES PURAS)**

> *Functions should be SMALL and SMART!!*

Pasamos ahora a la parte más que comentada ya, de que las funciones deben hacer 1 sóla cosa y no ocupar demasiadas líneas. Pongamos el ejemplo siguiente:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d0a9c69d-8ed7-4c72-9682-8ee3cbb2f18e/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d0a9c69d-8ed7-4c72-9682-8ee3cbb2f18e/Untitled.png)

Esta función recoge un elemento y lo renderiza en el DOM como una etiqueta HTML. Vemos que los nombres están bien claros y la identiación y formateo es correcto. Pero no es una función perfecta, ni mucho menos.

Seríamos más precisos con algo como lo siguiente:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/38f8cc99-7630-4332-be1a-64dc54c63abf/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/38f8cc99-7630-4332-be1a-64dc54c63abf/Untitled.png)

**En este caso otorgamos funcionalidades específicas a funciones externas que se encargan de realizar algo concreto y devolvernos un resultado.**

Evidentemente ahora tendremos muchas funciones donde antes sólo había una. Pero estas son más específicas y fáciles de entender.

**Y una vez más ... las funciones DEBEN hacer una sóla cosa.** 

### ¿"One thing"?

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1ace272b-a090-49c4-88c7-140ea770220c/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1ace272b-a090-49c4-88c7-140ea770220c/Untitled.png)

¿Y qué son los niveles de abstracción?

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/823918f5-ff9f-46ef-bfd3-58193807e85a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/823918f5-ff9f-46ef-bfd3-58193807e85a/Untitled.png)

### Functions & Abstraction

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7d6863ba-0fb9-4d00-9ca9-0caeaf62b66f/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7d6863ba-0fb9-4d00-9ca9-0caeaf62b66f/Untitled.png)

En el primer caso, detemos bastante clara la verificación que se va a realizara para determinar si es un EMAIL o no. No así en el segundo, en la que desconocemos qué verificaciones se van a tener que hacer al guardar un usuario.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d26c9457-f8df-4098-bf06-4ebf00e3b61b/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d26c9457-f8df-4098-bf06-4ebf00e3b61b/Untitled.png)

Procura mantener siempre los mismos niveles de abstracción dentro de las funciones.

Se hace necesario entonces, en la mayoría de los casos, reducir la complejidad de las funciones cuando su nivel de abstracción es alto, pero **¿cuándo o en qué casos debemos realizar el "corte" o la generación de una función diferenciada?**

En el vídeo se habla de una regla de oro ...

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cda1b2fd-f03f-4ce8-9f6a-3cb683ab051c/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cda1b2fd-f03f-4ce8-9f6a-3cb683ab051c/Untitled.png)

Vamos ahora a ver todo esto de la complejidad en funciones, con un ejemplo:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a9d0c400-2115-4a29-b390-a381db1d5bd8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a9d0c400-2115-4a29-b390-a381db1d5bd8/Untitled.png)

Se diferencian niveles de ABSTRACCIÓN: en rojo LOW LEVEL, en verde HIGH LEVEL

## Ejercicio sobre como "limpiar" / refactorizar una función

Nota: he seguido más o menos lo que se indica en el curso y además, aunque no es necesario en este caso, he añadido **notación JS Doc** para refrescar lo aprendido. Evidentemente son funciones tan básicas que no requieren de esta notación, pero por poner un ejemplo....

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/61111fe4-328f-4aaf-b7c4-ef9b05e8f471/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/61111fe4-328f-4aaf-b7c4-ef9b05e8f471/Untitled.png)

## Don't repeat yourself (DRY)

La madre de las reglas en programación. ¡No te repitas tío!

No escribas el mismo código o uno similar en más de un sitio, porque si luego quieres cambiar algo, lo vas a tener que hacer en varios sitios diferentes.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/04d43999-d620-4aef-b0dc-1b083ffe5765/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/04d43999-d620-4aef-b0dc-1b083ffe5765/Untitled.png)

## Don't overdo it

**No te pases "reduciendo" funciones si no es necesario. Usa la lógica y el sentido común en cada caso.**

Un ejemplo ...

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9eb00fee-37c2-4004-93b4-9ea7738a5c74/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9eb00fee-37c2-4004-93b4-9ea7738a5c74/Untitled.png)

Esta función tiene diferentes niveles de abstracción internos, por lo que si somos puristas, tendríamos que realizar la siguiente conversión:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ad32d15a-a805-466b-b6b9-2ebd143eb04d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ad32d15a-a805-466b-b6b9-2ebd143eb04d/Untitled.png)

Esto no la hace más "legible", así que no es del todo útil y lo único que hemos hecho es añadir un punto más de complejidad al código. Quizá estuviera mejor generar una CLASE que se encargue de manejar al usuario:

```jsx
class User{
	constructor(email, password){
		this.email = email;
		this.password = password;
	}

	saveUser(){
		database.insert(this);
	}
}
```

Y con esta clase podemos reestructurar la función así:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/13f909b5-272b-47b6-89d1-946979770b0a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/13f909b5-272b-47b6-89d1-946979770b0a/Untitled.png)

## Try keeping functions pure

Recuerda, una función pura es aquella que **para un mismo INPUT devuelve siempre un mismo OUTPUT**. Es un concepto fundamental de la **PROGAMACIÓN FUNCIONAL**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e38d5bd4-3f97-495f-a70f-56471598ceef/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e38d5bd4-3f97-495f-a70f-56471598ceef/Untitled.png)

No deberían tener "side effects". Pero esto es inevitable en casos concretos.

Los únicos SIDE EFFECTS tolerables serán aquellos que produzcan efectos controlados.

**Los SIDE EFFECTS inesperados o incontrolados, deben ser evitados**

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b937c332-8cfa-48e1-a5b2-713793af8008/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b937c332-8cfa-48e1-a5b2-713793af8008/Untitled.png)

La siguiente función produce un *side effect:*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/80447670-e365-4f9d-8cb0-aef26d6220fb/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/80447670-e365-4f9d-8cb0-aef26d6220fb/Untitled.png)

Pero en este caso es necesaria en caso de que tengamos que reutilizar la variable `lastAssignedId` en más casos una vez que tenga el ID de usuario cargado.

¡El nombre de las funciones es importante también en este caso! Podemos dejar claro qué funciones producen un SIDE EFFECT:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0092367a-7c37-4ec8-8e1b-2225ee0945fd/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0092367a-7c37-4ec8-8e1b-2225ee0945fd/Untitled.png)

Para resumir este apartado:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9709f5d8-2c02-4419-b9c4-bb23a0f953ab/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9709f5d8-2c02-4419-b9c4-bb23a0f953ab/Untitled.png)

## Side effects example

Pongamos un ejemplo de código en el que vamos a trabajar para reducir los "side effects" y aplicar los conceptos que hemos aprendido en este módulo:

```jsx
function connectDatabase() {
  const didConnect = database.connect(); // esta conexión a la base de datos es un SIDE EFFECT
  if (didConnect) {
    return true;
  } else {
    console.log('Could not connect to database!');
    return false;
  }
}

// todo correcto por el frente
function determineSupportAgent(ticket) {
  if (ticket.requestType === 'unknown') {
    return findStandardAgent();
  }
  return findAgentByRequestType(ticket.requestType);
}

// en este caso, esperamos simplemente un TRUE or FALSE como resolución, en su lugar obtenemos también un log en la consola
function isValid(email, password) {
  if (!email.includes('@') || password.length < 7) {
    console.log('Invalid input!');
    return false;
  }
  return true;
}
```

La mejor solución para este ejercicio sería la siguiente:

```jsx
function initApp() {
  try {
    connectDatabase();
  } catch (error) {
    console.log(error.message);
    // showErrorMessage(...)
  }
}

function connectDatabase() {
  const didConnect = database.connect();
  if (!didConnect) {
    throw new Error('Could not connect!');
  }
}

function determineSupportAgent(ticket) {
  if (ticket.requestType === 'unknown') {
    return findStandardAgent();
  }
  return findAgentByRequestType(ticket.requestType);
}

function isValid(email, password) {
  return email.includes('@') && password.length >= 7;
}
```

## Unit testing help!!

Los test unitarios, como para tantas otras cosas, son útiles también para valorar la calidad de nuestras funciones. Debemos plantearnos:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7dc3b846-3ed2-4af3-a4b5-42c7f377743d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7dc3b846-3ed2-4af3-a4b5-42c7f377743d/Untitled.png)

**Si la complejidad de la función es tal que nos impide realizar unos test "sencillos" y claros, es entonces cuando debemos plantearnos el "reducir" dicha función**

### Resumen del módulo

[Functions-Summary.pdf](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b5617eb9-f8e0-4390-bdf5-d96a39eee610/Functions-Summary.pdf)

---

# Control Structures & Errors

En este módulo trabajaremos con el objetivo de "mejorar" las estructuras de control que llevamos a cabo (if-else, bucles ...)

Esto es una mierda, para que nos vayamos entendiendo.... (tiene una complejidad notable). Y vamos a mejorarlo notablemente durante el módulo:

[academind/clean-code-course-code](https://github.com/academind/clean-code-course-code/blob/control-01-guards/dirty-control-structures.js)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f649811f-9caf-401b-a733-49a20d0408b7/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f649811f-9caf-401b-a733-49a20d0408b7/Untitled.png)

Así por encima, se enumeran las claves para una estructura de código limpia, que son las siguientes:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/89e3f086-8979-41ee-bd18-6495b266b172/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/89e3f086-8979-41ee-bd18-6495b266b172/Untitled.png)

Se entrará al detalle en cada una de ellas a lo largo del módulo.

## Use Guards & Fail Fast

¿Qué significa esto?, que en lugar de tener una ristra de código condicionado a un resultado positivo, podemos añadir una excepción que limite la ejecución de dicho código, es fácil:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3a36407d-48c5-47b4-a9f4-8455ce4aeac8/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3a36407d-48c5-47b4-a9f4-8455ce4aeac8/Untitled.png)

Prevenimos la ejecución del código si no se cumple dicha condición. Es un recurso fácil de leer y de comprender

Por mucho código condicionado anidado que tengamos, siempre podemos encontrar formas de añadir estos **Guards** a nuestra locura de código:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/10ca5d9e-8d64-439a-91e7-5f39ecf1b6c0/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/10ca5d9e-8d64-439a-91e7-5f39ecf1b6c0/Untitled.png)

**Es una técnica muy útil para eliminar anidamientos innecesarios**

Volviendo al ejemplo del principio, vamos a aplicar este concepto aprendido:

```jsx
function processTransactions(transactions) {
	if (!transactions || transactions.length === 0) {
		console.log('No transactions provided!');
		return;
	}

	for (const transaction of transactions) {
		if (transaction.status !== 'OPEN'){
			console.log('Invalid transaction type');
			continue;
		}
		if (transaction.type === 'PAYMENT'){
			// do something smart
		}
	}
}
```

**En un bucle no deberíamos introducir un RETURN ni BREAK, sino un CONTINUE para no paralizarlo .... [https://www.w3schools.com/js/js_break.asp](https://www.w3schools.com/js/js_break.asp)**

Teniendo en cuenta conceptos ya vistos como el de mantener un nivel de abstracción uniforme y el de usar "POSITIVE CHECKS", podríamos darle una vuelta a la primera parte de nuestro código, en la que se chequea la validez inicial de la transacción:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/014a96b1-d46c-47d6-a957-efc885047e7d/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/014a96b1-d46c-47d6-a957-efc885047e7d/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8c9985d8-41aa-47b0-b67d-1462ecd4f5a3/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8c9985d8-41aa-47b0-b67d-1462ecd4f5a3/Untitled.png)

## Extracting control structures into functions

Lo siguiente que vamos a realizar es separar la lógica del bucle que se lleva a cabo dentro de la función `processTransactions` en una función separada:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a44872e6-a0bf-4680-b3e0-fe5376b1d11a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a44872e6-a0bf-4680-b3e0-fe5376b1d11a/Untitled.png)

Lo mismo hacemos dentro de la función `processTransaction` para reducir la complejidad de tanto condicional anidado:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/68b624fe-cfef-4d4c-9e5c-bb3ab3bb677f/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/68b624fe-cfef-4d4c-9e5c-bb3ab3bb677f/Untitled.png)

Revisa el código inicial, por si no recuerdas como estaba ....

## Embrace Errors & Error Handling

Una regla sencilla... "si algo es un error → ¡produce un error"

¿Qué quiere decir con esto?

Que no puedes controlar absolutamente todas las variables de un cliente o servidor mediante condicionales.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9111d190-6ffd-4758-ba85-410b4a8dfb35/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9111d190-6ffd-4758-ba85-410b4a8dfb35/Untitled.png)

Casi todos los lenguajes de programación de hoy en día tienen métodos para controlar y manejar errores

Una buena forma de gestionarlos podría ser la siguiente:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/42d94727-e7f7-4342-bf19-ca733eb4b054/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/42d94727-e7f7-4342-bf19-ca733eb4b054/Untitled.png)

En el condicional que hace de "catch" dentro de `processTransaction` estamos lanzando un error, que paraliza la ejecución de código.

Hecho esto, lo gestionamos mediante el bloque `try {} catch(err) {}` que se encargará de hacer algo con él (en este caso mostrarlo en pantalla)

**Como nota, cabe decir una vez más, que el proceso de refactorización es contínuo y constante, como estamos viendo. Y que siempre podemos hacer "algo más" para mejorar**

Para terminar con el manejo de errores, se nos comenta que:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/92714c77-44d4-48a9-a9bb-d2b597de1522/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/92714c77-44d4-48a9-a9bb-d2b597de1522/Untitled.png)

¿Qué significa?

Que tenemos que considerar la funcionalidad vertida dentro del bloque `try{}catch(){}` como una única función. Es decir, la consideramos como bloque en su conjunto.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/565afb14-355d-4d13-b908-dae83cefa559/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/565afb14-355d-4d13-b908-dae83cefa559/Untitled.png)

## Factory functions & Polymorphism

Una "**factory function**", según definición del curso, es una función que utilizamos para producir algo (objetos, maps, array ...)

**Polymorphism**, es un concepto de generación de clases de forma "condicionada" a la inclusión de determinados parámetros:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8f070194-019a-4933-b769-8f2af69f8a48/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8f070194-019a-4933-b769-8f2af69f8a48/Untitled.png)

Siempre la llamamos igual pero genera un objeto que depende de los argumentos que le pasemos a dicha función.

**En el código lo has visto varias veces pero... procura no duplicar STRING, es mejor que utilices CONST o ENUM en TS**

### Final code

[academind/clean-code-course-code](https://github.com/academind/clean-code-course-code/tree/control-12-finished/final-demo)

### Resumen del módulo

[Control-Structures-Summary.pdf](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f680135a-6ea8-4d3a-8c69-1fe9339477a3/Control-Structures-Summary.pdf)

---

# Objects, classes & data containers / structures

## Difference between Objects & Data Structures

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e95ce922-a45a-494c-9874-c625b55aaab0/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e95ce922-a45a-494c-9874-c625b55aaab0/Untitled.png)

Teniendo en cuenta estas diferencias, se pone un ejemplo de Objeto y de Data Container:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6b8f78e5-e608-433f-b63d-3e55f2f4c718/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6b8f78e5-e608-433f-b63d-3e55f2f4c718/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2cdd4ac0-212a-4ff3-9a46-8b74e6e7744b/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2cdd4ac0-212a-4ff3-9a46-8b74e6e7744b/Untitled.png)

La clase  "**Database**" nos permite mantener y gestionar toda la lógica de la conexión con la base de datos, el hecho de que las propiedades sean privadas impide que se gestione una conexión directamente contra esta sin utilizar uno de los métodos preconfigurados, pongamos por ejemplo `this.connection.close()` cosa que sería errónea.

En cambio, las clases que simplemente son **generadoras de objetos**, nos ayudan a instanciarlas para, por ejemplo, pasar un usuario como argumento de una función:

```jsx
doSomething(new UserCredentials('pepe@pepe.com', '12345678!'));
```

> ***Polymorphism: "The ability of an object to take on many forms"***

## Classes should be Small

Al igual que ocurre con las functiones, es preferible tener varias CLASES pequeñas sobre unas pocas grandes.

**Una de las cuestiones más importantes a tener en cuenta sobre las clases es que deben tener una responsabilidad única (Single Responsibility Principle (SRP))**

Parece absurdo, pero se nos dice que, si por ejemplo, tenemos una clase PRODUCT, esta será encargada de manejar cuestiones relacionadas con el producto, no con cambiar los datos del usuario, por ejemplo.

Se ponen un ejemplo de una clase como la siguiente:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/431a0a9d-15c9-4b03-851e-02656316da69/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/431a0a9d-15c9-4b03-851e-02656316da69/Untitled.png)

Esto es un "cristo", porque lidiamos en la misma clase con pedidos, ofertas, usuarios, compradores ....

Deberíamos reducir notablemente la clase para generar varias que se encargen de  responsabilidades concretas:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b46a86d3-7313-4729-b428-07ec79699a85/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b46a86d3-7313-4729-b428-07ec79699a85/Untitled.png)

Ten en cuenta que, a diferencia de las funciones, NO se pide que las clases hagan 1 sóla cosa, sino que se encarguen de 1 sóla cosa. Es diferente:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/72151e1c-c85b-4d66-a843-30f59a83fa60/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/72151e1c-c85b-4d66-a843-30f59a83fa60/Untitled.png)

En el ejemplo, la clase Product, tiene una responsabilidad única, que es gestionar el producto, pero se encarga de hacer varias cosas: actualizar el producto, eliminarlo ... (podría poder añadirlo, cambiarlo ...)

## Cohesion

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1923ac82-7cfe-491b-bb2e-a242c3794062/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1923ac82-7cfe-491b-bb2e-a242c3794062/Untitled.png)

La clave está en crear clases con una "alta cohesión", ya que es casi imposible lograr el 100%.

Normalmente, cuanto más "reducidas" son las clases, más cohesión conseguimos al hacer que los métodos de estas usen las propiedades del propio objeto. 

## Law of Demeter

La "ley de demetrio" (valga la coña) nos dice que no debemos profundizar en propiedades internas de objetos de "extraños":

```jsx
this.customer.lastPurchase.date;
```

*La excepción es cuando accedemos a estructuras de datos propias, que conocemos.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/be0e97d6-838b-4897-a0f2-e85233d7b0fd/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/be0e97d6-838b-4897-a0f2-e85233d7b0fd/Untitled.png)

Lo normal sería poder acceder a un método "get" que nos devolviera la propiedad que estamos solicitando: 

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ce501efe-45b4-4672-a8fb-d1f2ba4928dd/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ce501efe-45b4-4672-a8fb-d1f2ba4928dd/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/767dc790-fc8a-4a7d-a93f-6f5b2ea739f1/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/767dc790-fc8a-4a7d-a93f-6f5b2ea739f1/Untitled.png)

Pero esto casi nunca se va a dar. No tenemos un método para devolver cada una de las propiedades internas del objeto.

La solución más óptima pasa por tener en cuenta el principio:

> *Tell, not ask!*

En el ejemplo, le pasamos la propiedad `lastPurchase` del `customer` al método que va a trabajar con ella:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9a3c86cb-a06b-4e91-8d3d-76c174a64e16/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9a3c86cb-a06b-4e91-8d3d-76c174a64e16/Untitled.png)

Y ya internamente gestionaremos la fecha.

*[ 🧙🏾‍♂️  Esto no lo termino de ver del todo ...]*

## The SOLID principles

Aplicable cuando trabajamos con clases, OOP.

**S → Single Responsibility Principle**

**O → Open-Closed Principle**

**L → Liskov Substitution Principle**

**I → Interface Segregation Principle**

**D → Dependency Inversion Principle**

### The Single-Responsibility Principle (SRP)

*Classes should have a SINGLE RESPONSIBILITY. A class shouldn't CHANGE FOR MORE THAN ONE REASON.*

Mediante los siguientes ejemplos podemos entenderlo mejor:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2e0e1a38-4c84-47ce-beb3-53981ec5e05f/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2e0e1a38-4c84-47ce-beb3-53981ec5e05f/Untitled.png)

En el primer caso, `User`, en todos sus métodos estamos gestionando la autenticación del usuario.

En el segundo caso, `ReportDocument`, se ofrecen dos métodos que, aunque relacionados con el informe, son áreas diferenciadas dentro de la lógica de nuestro producto: no tiene relación el generar un reporte, gestionar sus datos internos ... con imprimir un PDF

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/de18352f-5ecb-4103-a857-643ef2bb1238/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/de18352f-5ecb-4103-a857-643ef2bb1238/Untitled.png)

### The Open-Closed Principle (OCP)

*A class should be open for extension but closed for modification*

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/69d6567e-1205-459a-a2d9-7afc66feb0b5/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/69d6567e-1205-459a-a2d9-7afc66feb0b5/Untitled.png)

Si queremos generar un documento word, excel... con la clase `Printer`, nos obligará a modificar la clase, ya que no tenemos métodos genéricos (sólo para imprimir un PDF, un documento web ...)

Necesitamos generar `clases` e `interfaces` que sean más versátiles y puedan ser "extendidas" por otras clases que vayamos a generar y que sean más específicas:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f8998b39-1245-4574-a8d2-b974e58ab920/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f8998b39-1245-4574-a8d2-b974e58ab920/Untitled.png)

¿Esto cómo nos afecta directamente con el objetivo primario del curso (CLEAN CODE)?

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/be0459aa-aca5-4d60-b2d1-7daef5f6b736/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/be0459aa-aca5-4d60-b2d1-7daef5f6b736/Untitled.png)

Los dos primeros principios SOLID son los que más nos afectan en cuanto al CLEAN CODE, pero no vamos a desaprovechar la oportunidad de saber acerca de los otros tres:

### Liskov Substitution Principle

> *Objects should be replaceable with instances of their subclasses without altering the behavior*

Veamos un ejemplo:

```jsx
class Bird {
	fly(){
		//...fly
	}
}

class Eagle extends Bird {
	dive(){
		//...dive
	}
}
```

Con esto podemos crear una instancia de la clase Bird y llamar al método FLY:

```jsx
const bird = new Bird();

bird.fly(); //...fly
```

El principio de LISKOV nos dice que deberíamos ser capaces de instanciar cualquiera de las subclases y tener acceso a los mismos métodos, al menos:

```jsx
const eagle = new Eagle();

eagle.fly() // ...fly
eagle.dive() // ...dive
```

Peeero, imaginemos que queremos crear la clase `Penguin` (pista: los pingüinos no vuelan):

```jsx
class Penguin extends Bird {
	//penguin don't fly!!
}
```

Esto nos daria una pista de que no hemos respetado "con pureza" el principio que estamos tratando, y que quizá debieramos modificar la clase `Bird` y crear una nueva:

```jsx
class Bird {
	// something common in all birds
}

class FlyingBird {
	fly(){
		//...fly
	}
}
```

Entonces ya podríamos hacer:

```jsx
class Penguin extends Bird {
 //...
}
```

### Interface Segregation Principle

> *Many client-specific interfaces are better than one general purpose interface*

...what ? 

Una vez más, lo vemos mejor con un ejemplo:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/986e9ca8-4814-41da-87cf-455d9c433c52/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/986e9ca8-4814-41da-87cf-455d9c433c52/Untitled.png)

Parece que bien, ¿no?. Pero qué ocurre si queremos generar otra clase como la siguiente:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b2122350-e9df-43f8-8390-2ffb77a71211/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b2122350-e9df-43f8-8390-2ffb77a71211/Untitled.png)

En este caso, al tratarse de la memoria local, no tiene ningún sentido el método conect, pero se nos hace obligatorio al haber implementado la **INTERFACE `Database`**

Nada, pues la hemos liado con la interface, toca darle una vuelta (vuelve a leer la "quote" inicial de este principio)

Siguiendo la idea planteada, generamos mejor dos Interfaces diferenciadas:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3b151504-532c-4870-8f25-51d29e111bfe/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3b151504-532c-4870-8f25-51d29e111bfe/Untitled.png)

Que ahora nos pemite en cada clase seleccionar las que van a ser "implementadas":

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/230e90f6-96e2-44fd-a07b-d8df8fa93913/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/230e90f6-96e2-44fd-a07b-d8df8fa93913/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/50f385ee-b6fa-44f4-8b33-25bd3caa0613/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/50f385ee-b6fa-44f4-8b33-25bd3caa0613/Untitled.png)

### Dependency Inversion Principle

> *You should depend upon abstractions, not concretions*

¿Mande?

No queda otra que explicarnos con un ejemplo:

Partiendo del último ejemplo visto en el que hemos creado la clase `SQLDatabase` y `InMemoryDatabase`, vamos a crear ahora una clase `App` que recibe como parámetro una instancia de estas y, en función de cuál sea actúa de una forma determinada:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/572afab9-3814-459a-b378-930d5bdbcf01/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/572afab9-3814-459a-b378-930d5bdbcf01/Untitled.png)

¿Qué ocurre si en lugar de dos instancias de dos clases tenemos 20?, ¿comprobaremos una a una con un `if...` ?

No. Lo mejor en este caso es que recojamos como parámetro la interfaz común a todas (en este caso `Database`) y externamente a esta clase `App`, nos encarguemos de realizar la conexión u otros métodos que puedan llevar a cabo instancias del parámetro de partida:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dd24db25-9cb1-4dd7-84f9-bf83c22f2f40/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dd24db25-9cb1-4dd7-84f9-bf83c22f2f40/Untitled.png)

### Resumen del módulo

[Objects-Summary.pdf](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fb6fe9ed-6da9-47cb-84d4-ccadbfe809c1/Objects-Summary.pdf)

---

# Summary & checklist

Hacemos un resumen de las ideas fundamentales vistas hasta ahora:

- "Clean code" es código que es fácilmente legible y comprensible por HUMANOS

Las áreas más importantes que debemos controlar cuando escribimos "clean code" son:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7c6433c8-0d1a-4af9-b493-6d37149356f0/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7c6433c8-0d1a-4af9-b493-6d37149356f0/Untitled.png)

Rescatamos las claves de cada una de ellas:

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3785a093-e8cf-42a6-ba89-b3357767d254/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3785a093-e8cf-42a6-ba89-b3357767d254/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/25060e41-aa40-4ee9-aa75-bb9c2664b383/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/25060e41-aa40-4ee9-aa75-bb9c2664b383/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/834467f4-6e6b-44b4-bf3a-f2d521b44136/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/834467f4-6e6b-44b4-bf3a-f2d521b44136/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fc65b1f7-78d5-490e-b8be-23c9db5decfb/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fc65b1f7-78d5-490e-b8be-23c9db5decfb/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d5c580e8-7299-4aae-8426-4d275e5739a6/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d5c580e8-7299-4aae-8426-4d275e5739a6/Untitled.png)

---

# Recursos

[academind/clean-code-course-code](https://github.com/academind/clean-code-course-code/tree/general-resources)

El repo en el que ha colgado un PDF muy interesante con todo el contenido del curso. ¡DESCÁRGALO!
