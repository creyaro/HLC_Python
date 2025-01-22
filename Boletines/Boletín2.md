## **Boletín 2: Condicionales y Bucles Avanzados**

### **Ejercicio 1**
Crea un programa que pida al usuario su edad y determine si puede votar. Recuerda que para votar debe tener al menos 18 años.

```python
# Ejemplo:
# Entrada del usuario: 16
# Salida: No puedes votar.
```


### **Ejercicio 2**
Escribe un programa que pida al usuario tres números y determine cuál es el mayor. Si hay un empate entre dos o más números, indícalo también.

```python
# Ejemplo:
# Entrada del usuario: 5, 10, 10
# Salida: Hay un empate entre los mayores: 10 y 10.
```


### **Ejercicio 3**
Diseña un programa que solicite al usuario una calificación entre 0 y 10. Luego, muestra si la calificación corresponde a "Aprobado" (>= 5) o "Suspenso" (< 5).

```python
# Ejemplo:
# Entrada del usuario: 7
# Salida: Aprobado.
```


### **Ejercicio 4**
Escribe un programa que simule un sistema de contraseñas. Pide al usuario que ingrese una contraseña y verifica si coincide con una contraseña previamente definida (por ejemplo, "secreta123"). Si falla tres veces, muestra un mensaje de bloqueo.

```python
# Ejemplo:
# Entrada del usuario: secreta123 (tras 2 intentos fallidos)
# Salida: ¡Bienvenido!
# Entrada del usuario: 3 intentos fallidos
# Salida: ¡Cuenta bloqueada!
```


### **Ejercicio 5**
Crea un programa que pida al usuario un número y determine si es par o impar utilizando un operador ternario.

```python
# Ejemplo:
# Entrada del usuario: 7
# Salida: El número 7 es impar.
```


### **Ejercicio 6**
Escribe un programa que pida al usuario una palabra y verifique si contiene alguna de las siguientes letras especiales: `@`, `#`, `$`, `%`. Si la palabra contiene al menos una, muestra un mensaje indicando cuál.

```python
# Ejemplo:
# Entrada del usuario: Python@
# Salida: La palabra contiene el símbolo @.
```


### **Ejercicio 7**
Crea un programa que genere los primeros 10 números de la serie de Fibonacci y los imprima.

```python
# Ejemplo:
# Salida: [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
```


### **Ejercicio 8**
Escribe un programa que pida al usuario un número entero positivo y genere una lista con los cuadrados de todos los números desde 1 hasta ese número (incluido), utilizando una lista por comprensión.

```python
# Ejemplo:
# Entrada del usuario: 5
# Salida: [1, 4, 9, 16, 25]
```


### **Ejercicio 9**
Escribe un programa que simule un juego de adivinanza. El programa debe generar un número aleatorio entre 1 y 50, y el usuario debe adivinarlo. Proporciona pistas como "Más alto" o "Más bajo" hasta que el usuario lo adivine correctamente.

```python
# Ejemplo:
# Salida: Adivina el número (entre 1 y 50): 25
# Entrada del usuario: 30
# Salida: Más bajo.
# Entrada del usuario: 25
# Salida: ¡Correcto!
```

**💡Nota**: Para generar un número aleatorio en Python, se usa el siguiente código:

```python
import random

numero = random.randint(1, 10) # Número aleatorio entre 1 y 10 (ambos incluidos)
```

### **Ejercicio 10**
Escribe un programa que use un bucle para imprimir un triángulo de estrellas (★) basado en un número dado por el usuario. Por ejemplo, si el usuario ingresa 4:

```python
# Ejemplo:
# Entrada del usuario: 4
# Salida:
# ★
# ★★
# ★★★
# ★★★★
```
