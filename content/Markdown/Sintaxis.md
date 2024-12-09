+++
date = '2024-12-09T16:14:03+01:00'
draft = false
title = 'Sintaxis'
+++

## Encabezados

Las # almohadillas son uno de los métodos utilizados en Markdown para crear encabezados. Debes usarlos añadiendo uno por cada nivel.

```markdown
# Encabezado Nivel 1
## Encabezado Nivel 2
### Encabezado Nivel 3
#### Encabezado Nivel 4
```
**Se visualiza como:**

# Encabezado Nivel 1
## Encabezado Nivel 2
### Encabezado Nivel 3
#### Encabezado Nivel 4

## Listas
A diferencia de lo que ocurre en HTML, generar listas en Markdown es tremendamente sencillo. Se pueden encontrar de dos tipos.

#### Listas ordenadas

Para crear listas ordenadas debes utilizar la sintaxis de tipo: «número.» 1. Al igual que ocurre con las listas desordenadas, también podrás anidarlas o combinarlas.

```Markdown
1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        1. Elemento de lista 5
        2. Elemento de lista 6
```
**Se visualiza como:**
1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        1. Elemento de lista 5
        2. Elemento de lista 6

#### Listas desordenadas

Para crear listas desordenadas utiliza * asteriscos, - guiones, o + símbolo de suma.

```Markdown
- Elemento de lista 1
- Elemento de lista 2
* Elemento de lista 3
* Elemento de lista 4
+ Elemento de lista 5
+ Elemento de lista 6
```
Da igual qué elemento se escoja, incluso se pueden intercambiar. Todos se verán igual al procesarse.

**Se visualiza como:**
- Elemento de lista 1
- Elemento de lista 2
- Elemento de lista 3
- Elemento de lista 4
- Elemento de lista 5
- Elemento de lista 6

## Tablas

Se puede crear tablas fácilmente usando guiones - y barras verticales |:

```markdown
| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Fila 1    | Dato 1.1  | Dato 1.2  |
| Fila 2    | Dato 2.1  | Dato 2.2  |
```
**Se visualiza como:**

| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Fila 1    | Dato 1.1  | Dato 1.2  |
| Fila 2    | Dato 2.1  | Dato 2.2  |

## Imágenes
Para insertar imágenes, hay que utilizar la sintaxis `![Texto alternativo](/ruta/a/la/imagen.jpg "Título alternativo")`

El texto alternativo es lo que se mostraría si la carga de la imagen fallase.
También se puede añadir un título alternativo entrecomillándolo al final de la ruta. Esto sería el título mostrado al dejar el cursor del ratón sobre la imagen.

**Se visualiza como:**

![Logo de Hugo](https://gohugo.io/img/hugo-logo.png "Logo Hugo")