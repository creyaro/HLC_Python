# Introducción a Python


## **¿Qué es Python?**
Python es un lenguaje de programación fácil de aprender, versátil y utilizado en diversas áreas, como:
- Desarrollo web 🌐
- Ciencia de datos 📊
- Inteligencia artificial 🤖
- Automatización de tareas ⚙️

Tiene las siguientes características:

- Interpretado: Se ejecuta línea por línea, sin necesidad de compilar antes de ejecutarlo.
- Multiplataforma: Funciona en distintos sistemas operativos como Windows, macOS y Linux.
- Multiparadigma: Soporta programación estructurada, orientada a objetos y funcional.

Además, Python es un lenguaje de tipado dinámico y fuerte. Esto significa que no necesitas especificar el tipo de dato al declarar una variable, ya que Python lo determina automáticamente en tiempo de ejecución. Además, al ser de tipado fuerte, no permite combinaciones de tipos incompatibles sin conversión explícita, evitando errores inesperados. Aunque no es obligatorio, Python permite usar anotaciones de tipo para indicar el tipo de datos que deberían usarse, lo que mejora la legibilidad y mantenimiento del código sin afectar su ejecución.


---

## **Impresión por pantalla**
La función `print()` se utiliza para mostrar mensajes en la pantalla. A continuación, un ejemplo básico:

```python
print("¡Hola, mundo!")
```

**Resultado:**
```
¡Hola, mundo!
```

---

## **Variables**
Una **variable** es un espacio en memoria donde se almacena un valor.

### **Tipos básicos de variables**
- **Enteros (`int`)**: Números sin decimales.
- **Flotantes (`float`)**: Números con decimales.
- **Cadenas de texto (`str`)**: Texto delimitado por comillas.
- **Booleanos (`bool`)**: Valores de verdadero o falso.

### **Ejemplos:**
```python
# Definición de variables
nombre = "Ana"  # Texto (str)
edad = 25        # Número entero (int)
peso = 62.5      # Número decimal (float)
es_estudiante = True  # Booleano (bool)

# Mostrar los valores
print("Nombre:", nombre)
print("Edad:", edad)
print("Peso:", peso)
print("Es estudiante:", es_estudiante)
```

---

## **Operaciones básicas**
Es posible realizar operaciones matemáticas simples en Python:

```python
# Suma y resta
x = 10 + 5
y = 20 - 3
print("Suma:", x)
print("Resta:", y)

# Multiplicación y división
a = 4 * 3
b = 10 / 2
print("Multiplicación:", a)
print("División:", b)

# Potencias
c = 2 ** 3
print("Potencia (2^3):", c)
```

---

## **Entrada del usuario**
La función `input()` permite recibir datos ingresados por el usuario:

```python
# Solicitar el nombre del usuario
nombre = input("¿Cómo te llamas? ")
print("Hola,", nombre, "¡Bienvenido a Python!")
```

**Ejercicio:**
1. Solicitar al usuario su edad.
2. Calcular cuántos años tendrá en 5 años.

```python
edad = int(input("¿Cuántos años tienes? "))
edad_futura = edad + 5
print("En 5 años tendrás", edad_futura, "años.")
```

---

## **Condicionales básicos**
Los condicionales permiten tomar decisiones en el programa utilizando `if` y `else`:

```python
# Ejemplo de condicional
edad = int(input("¿Cuántos años tienes? "))
if edad >= 18:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")
```

---

## **Funciones**
Las **funciones** son bloques de código reutilizables. Se definen utilizando `def`:

```python
# Definición de una función
def saludar(nombre):
    print("Hola,", nombre, "¡Es un gusto conocerte!")

# Llamadas a la función
saludar("Pedro")
saludar("Ana")
```

**Ejercicio:**
Crear una función que reciba un número y devuelva su cuadrado:

```python
# Función para calcular el cuadrado de un número
def cuadrado(numero):
    return numero ** 2

# Llamada a la función
resultado = cuadrado(4)
print("El cuadrado de 4 es:", resultado)
```

---

## **Conclusión**
En esta introducción se han abordado:
- El uso de `print()` para mostrar mensajes.
- La definición y manejo de variables.
- La recepción de datos del usuario con `input()`.
- La utilización de condicionales (`if`/`else`).
- La creación de funciones básicas.

Con estos conceptos, es posible empezar a desarrollar programas simples en Python. 🐍
