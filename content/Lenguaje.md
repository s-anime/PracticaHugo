+++
date = '2024-12-09T16:13:23+01:00'
draft = false
title = 'Lenguaje'
+++

### **¿Qué es Python?**

Python es un lenguaje de programación de alto nivel, interpretado y de propósito general. Es conocido por su sintaxis simple y legible, lo que lo hace ideal para principiantes y profesionales. Se usa en una amplia gama de aplicaciones, desde desarrollo web, ciencia de datos, inteligencia artificial, hasta automatización de tareas.

**Características principales:**

- Fácil de aprender y leer: Su sintaxis es limpia y cercana al lenguaje humano.
- Multipropósito: Puede usarse para muchos tipos de aplicaciones.
- Extensibilidad: Tiene una enorme cantidad de bibliotecas (como NumPy, Pandas, Django, etc.).
- Multiplataforma: Funciona en Windows, macOS y Linux.


**Ejemplo más básico: Imprimir "Hola, mundo"**

```Python
print("Hola, mundo")
```

Explicación:

+ print() es una función que muestra texto en la pantalla.
+ El texto entre comillas "Hola, mundo" es un string (cadena de texto).

**Ejemplo sencillo: Programa para sumar dos números**

```Python
# Solicita dos números al usuario
numero1 = float(input("Ingresa el primer número: "))
numero2 = float(input("Ingresa el segundo número: "))

# Suma los números
suma = numero1 + numero2

# Imprime el resultado
print(f"La suma de {numero1} y {numero2} es: {suma}")
```

¿Cómo funciona?

1. Entrada del usuario: input() se usa para capturar texto que introduce el usuario.
2. Conversión de tipo: Se usa float() para convertir el texto en un número decimal.
3. Operación: Los números se suman con +.
4. Salida: print() muestra el resultado, utilizando una cadena formateada (f"...").