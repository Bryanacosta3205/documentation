---
id: doc0
title: Una breve introducción a Markdown
sidebar_label: Markdown
---

![][author] ![][twitter]

[author]: https://img.shields.io/badge/Author-Bryan%20Acosta-red
[twitter]: https://img.shields.io/twitter/follow/BryanEduardoGA

## Encabezados

> Para crear un encabezado, agrega un signo de número antes del texto y da un espacio. Cada signo de número añadido incrementa el nivel del encabezado.

```markdown
# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6
```

# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6

### Sintaxis alternativa de encabezados

> Como alternativa, en la línea debajo del texto, agregue los siguientes caracteres.

`===` Equivale a `# Heading level 1`  
`---` Equivale a `# Heading level 2`

# Heading level 1

## Heading level 2

---

## Parrafos

> Para crear parrafos utilice una línea en blanco para separar las líneas de texto.

```html
Este es un párrafo en Markdown.
<!--Línea en blanco-->
Este es otro párrafo de Markdown.
```

`<!-- Párrafo SIN línea en blanco -->`  
Este es un párrafo  
en Markdown.
Este es otro párrafo  
de Markdown.  
`<!-- Párrafo CON línea en blanco -->`  
Este es un párrafo  
en Markdown.

Este es otro párrafo  
de Markdown.

---

## Saltos de línea

> Para crear un salto de línea, finalice una línea con dos espacios para indicar un salto.

```markdown
Me gusta mucho usar
Markdown.

Me gusta mucho usar(dos espacios)
Markdown.

Me gusta mucho usar<br>
Markdown
```

Me gusta mucho usar
Markdown.

Me gusta mucho usar  
Markdown.

Me gusta mucho usar <br>
Markdown.

---

## Énfasis

> Puedes agregar énfasis al texto añadiendo texto en remarcado o cursiva.

### Remarcado

> Para agregar texto remarcado, añade dos asteriscos ( \* ) antes y despues de la palabra que se pretende enfatizar.

### Cursiva

> Para agregar texto en itálica, añade un asterisco ( \* ) antes y despues de la palabra que se pretende enfatizar.

### Remarcado y cursiva

> Para agregar texto remarcado y cursivo, añade tres asteriscos ( \* ) antes y despues de la palabra que se pretende enfatizar.

### Tachado

> Para agregar texto tachado, añade dos virgulillas ( ~ ) antes y despues de la palabra que se pretende enfatizar.

```markdown
Este es un texto **remarcado**

Este es un texto en _cursiva_

Este es un texto en **_remarcado y cursiva_**

Este es un texto ~~tachado~~
```

Este es un texto **remarcado**

Este es un texto en _cursiva_

Este es un texto en **_remarcado y cursiva_**

Este es un texto ~~tachado~~

---

## Citas en bloque

> Para crear una cita en bloque añade un ( > ) antes de un parrafo.

```markdown
> Esto es uns cita en bloque.
```

> Esto es uns cita en bloque.

### Citas en bloque con múltiples párrafos

```markdown
> Esto es una cita en bloque.
>
> con múltiples párrafos.
```

> Esto es uns cita en bloque con múltiples párrafos.
>
> Este es el segundo parrafo de la cita en bloque.

### Citas en bloque anidados

```markdown
> Esto es una cita en bloque anidada.
>
> > Soy la cita en bloque hija.
```

> Esto es una cita en bloque anidada.
>
> > Soy la cita en bloque hija.

---

## Listas

> Puedes ordenar elementos en listas ordenadas y desordenadas.

### Listas ordenadas

> Para crear **listas ordenadas** debes utilizar la sintáxis:  
> `[Número].`

```markdown
1. Raíz 1
   1. Hijo 1
   2. Hijo 2
2. Raíz 2
3. Raíz 3
```

1. Raíz 1
   1. Hijo 1
   2. Hijo 2
2. Raíz 2
3. Raíz 3

### Listas desordenadas

> Para crear **listas desordenadas** puedes utilizar los símbolos de:  
> `-` Guion  
> `*` Asterisco  
> `+` Suma

```markdown
- Raíz 1
  - Hijo 1
  - Hijo 2

* Raíz 2
* Raíz 3

- Raíz 4
- Raíz 5

  Yo no soy un elemento de lista, soy un párrafo!
  Si usarme quieres, indentarme debes.

* Raiz 6
```

- Raíz 1
  - Hijo 1
  - Hijo 2

* Raíz 2
* Raíz 3
  - Hijo 1
  * Hijo 2

- Raíz 4
- Raíz 5

  Yo no soy un elemento de lista, soy un párrafo!  
   Si usarme quieres, indentarme debes.

* Raíz 6

### Bloques de código en listas

> Los bloques de código normalmente tienen sangría de cuatro espacios o una tabulación. Cuando estén en una lista, indente ocho espacios o dos tabulaciones.

- 1.- Abrir el archivo HTML.
- 2.- Ubicar la primera línea de código.

        <html>
            <head>
                <title>Titulo</title>
            </head>
        </html>

- 3.- Modifica el titulo dentro de la etiqueta `<title>`.

---

## Código

> Para denotar una palabra o frase como código escríbala entre dos símbolos de acento grave ( `` ).

```markdown
En JavaScript para imprimir algo en consola utilizamos: `console.log()`
```

En JavaScript para imprimir algo en consola utilizamos: `console.log()`

### Bloques de código

> Existen dos métodos para crear bloques de código:  
> 1.- Indenta cada línea de código con cuatro espacios o una tabulación.
>
> 2.- Usar codigo cercado, esto se logra encerrando el código con tres símbolos de **acento grave** ( ``` ) ó tres símbolos de **virgulilla** ( ~~~ ) al inicio y al final.
>
> **Nota:** Se puede especificar el lenguaje al que se hace referencia después de los **acentos graves** ( ``` ) ó  
> **virgulillas** ( ~~~ ) de apertura.

````markdown
Método 1

    console.log('Este es el método uno')

Método 2

```javascript
console.log("Este es el método dos");
```
````

#### **Resultado**

    console.log('Este es el método uno')

```javascript
console.log("Este es el método dos");
```

---

## Reglas horizontales

> Se utilizan para separar secciones dentro de una misma página.
>
> Se identifican en un grupo de tres símbolos:
>
> Guion medio: `---`  
> Asterisco: `***`  
> Guion bajo: `___`

---

---

---

## Enlaces

> Para crear un enlace, encierre el texto del enlace entre corchetes y luego añade la dirección de enlace entre paréntesis.

```markdown
Yo almaceno las versiones de mis proyectos en [GitLab](https://GitLab.com)
```

Yo almaceno las versiones de mis proyectos en [GitLab](https://GitLab.com)

### Títulos a enlaces

> Opcionalmente, puede agregar un titulo a un enlace. Este aparecerá al poner el cursor sobre el enlace.

```markdown
Yo almaceno las versiones de mis proyectos en [GitLab](https://GitLab.com "Yo soy el título")
```

Yo almaceno las versiones de mis proyectos en [GitLab](https://GitLab.com "Yo soy el título")

### URLs y direcciones de correo

> Para convertir rapidamente una url o dirección de correo en un enlace, enciérrela entre corchetes angulares `<>` .

```markdown
<https://GitLab.com>
<fake@colima.tecnm.mx>
```

<https://GitLab.com>  
<fake@colima.tecnm.mx>

---

## Imágenes

> Para insertar una imagen, agregue el símbolo exclamación de cierre ( ! ) seguido por un texto `alt` entre corchetes, y la ruta de la imágen entre paréntesis.
>
> **Nota:** Puedes también añadir un título a la URL.

```markdown
![COVID-19](https://cdn.pixabay.com/photo/2020/03/16/16/29/virus-4937553_960_720.jpg "Imágen del COVID-19")
```

![COVID-19](https://cdn.pixabay.com/photo/2020/03/16/16/29/virus-4937553_960_720.jpg "Imágen del COVID-19")

### Imágenes con enlace

> Para añadir un enlace a una imágen, encierra el Markdown de la imágen en corchetes, y después agrega el enlace entre paréntesis.

```markdown
[
![COVID-19](https://cdn.pixabay.com/photo/2020/03/16/16/29/virus-4937553_960_720.jpg)
](https://www.google.com/coronavirus)
```

[
![COVID-19](https://cdn.pixabay.com/photo/2020/03/16/16/29/virus-4937553_960_720.jpg)
](https://www.google.com/coronavirus)

---

## Escapando caracteres

> Para mostrar un carácter literal que, de lo contrario se usaría para dar formato al texto de un documento Markdown, agregue una barra diagonal inversa ( \\ ) delante del carácter.

```markdwon
\* Sin la diagonal invertida, esto sería una viñeta en una lista desordenada.

* Prueba sin diagonal invertida.


```

\* Sin la diagonal invertida, esto sería una viñeta en una lista desordenada.

- Prueba sin diagonal invertida.

### Caracteres que puedes escapar

| Carácter        | Nombre                         |
| :-------------- | ------------------------------ |
| \               | Barra invertida                |
| ` |Acento grave |
| \*              | Asterisco                      |
| \_              | Guión bajo                     |
| { }             | Llaves                         |
| [ ]             | Corchetes                      |
| ( )             | Paréntesis                     |
| #               | Signo de número                |
| +               | Signo más                      |
| -               | Signo menos (guión)            |
| .               | Punto                          |
| !               | Signo de exclamación de cierre |
| &#124;          | Pipe                           |

## Tablas

## Extra

### Buenas prácticas

> Under construction!
