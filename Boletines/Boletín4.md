## **Boletín 4: Recursividad**

> **❗Nota**: En los ejercicios donde se pide convertir funciones de iterativas a recursivas hay que entregar las dos funciones.

### **Ejercicio 1: Factorial**
Escribe una función iterativa que calcule el factorial de un número y luego conviértela a recursiva.

```python
# Ejemplo:
# Entrada: 5
# Salida: 120
```

### **Ejercicio 2: Fibonacci**
Escribe una función recursiva que calcule el n-ésimo término de la sucesión de Fibonacci.

```python
# Ejemplo:
# Entrada: 6
# Salida: 8
```
> **💡 Recuerda**: La serie de Fibonacci se compone de los números [0, 1, 1, 2, 3, 5...] donde:

$$F(n) =
\begin{cases} 
0, & \text{si } n = 0 \\
1, & \text{si } n = 1 \\
F(n-1) + F(n-2), & \text{si } n \geq 2
\end{cases}
$$


### **Ejercicio 3: Potencia de un Número**
Escribe una función recursiva que calcule `base^exponente` sin usar operadores de potenciación.

```python
# Ejemplo:
# Entrada: (2, 3)
# Salida: 8
```

> **💡 Recuerda**: La potencia de un número se calcula multiplicando la base tantas veces como indique el exponente:

```math
2^3 = 2*2*2 = 8
```

### **Ejercicio 4: Suma de Dígitos**
Escribe una función recursiva que calcule la suma de los dígitos de un número entero positivo.

```python
# Ejemplo:
# Entrada: 1234
# Salida: 10
```

### **Ejercicio 5: Contar Dígitos**
Escribe una función recursiva que cuente el número de dígitos de un entero positivo.

```python
# Ejemplo:
# Entrada: 1234
# Salida: 4
```