## **Boletín 5: Programación Orientada a Objetos (POO)**

> **❗Nota**: En los ejercicios donde se pide modificar una clase o implementar un nuevo método, hay que entregar el código correspondiente con su salida de prueba.

### **Ejercicio 1: Clase "Persona"**
Crea una clase `Persona` con los atributos `nombre`, `edad` y `profesion`. Agrega un método `presentarse()` que devuelva un mensaje con su información.

```python
# Ejemplo de uso:
p = Persona("Ana", 28, "Ingeniera")
print(p.presentarse())

# Salida esperada:
# Hola, mi nombre es Ana, tengo 28 años y soy Ingeniera.
```

### **Ejercicio 2: Herencia - Clase "Estudiante"**
Extiende la clase `Persona` creando una subclase `Estudiante`, agregando un nuevo atributo `grado` y sobrescribiendo el método `presentarse()`.

```python
# Ejemplo de uso:
e = Estudiante("Carlos", 22, "Estudiante", "Matemáticas")
print(e.presentarse())

# Salida esperada:
# Hola, mi nombre es Carlos, tengo 22 años y estudio Matemáticas.
```

### **Ejercicio 3: Polimorfismo - Clase "Trabajador"**
Crea una nueva subclase `Trabajador` que sobrescriba `presentarse()` para que incluya su `empresa`.

```python
# Ejemplo de uso:
t = Trabajador("Elena", 35, "Arquitecta", "Construcciones XYZ")
print(t.presentarse())

# Salida esperada:
# Hola, mi nombre es Elena, tengo 35 años y trabajo en Construcciones XYZ.
```

### **Ejercicio 4: Encapsulamiento - Clase "CuentaBancaria"**
Crea una clase `CuentaBancaria` con un atributo `saldo`. Implementa métodos para consultar el saldo (`ver_saldo()`), depositar (`depositar(monto)`) y retirar (`retirar(monto)`) con validaciones.

```python
# Ejemplo de uso:
cuenta = CuentaBancaria(1000)
cuenta.depositar(500)
cuenta.retirar(300)
print(cuenta.ver_saldo())

# Salida esperada:
# 1200
```

### **Ejercicio 5: Abstracción - Clase "Figura"**
Crea una clase abstracta `Figura` con un método `calcular_area()`. Luego, crea las clases `Circulo` y `Rectangulo` que implementen este método.

```python
# Ejemplo de uso:
c = Circulo(5)
r = Rectangulo(4, 6)
print(c.calcular_area())  # Salida esperada: 78.54 (aproximadamente)
print(r.calcular_area())  # Salida esperada: 24
```

> **💡 Nota:** Usa `math.pi` para el cálculo del área del círculo.

### **Ejercicio 6: Relaciones entre Clases - Clase "Biblioteca"**
Crea una clase `Libro` con atributos `titulo` y `autor`. Luego, crea una clase `Biblioteca` que contenga una lista de libros y métodos para agregar libros y mostrarlos.

```python
# Ejemplo de uso:
biblio = Biblioteca()
biblio.agregar_libro(Libro("1984", "George Orwell"))
biblio.agregar_libro(Libro("Cien Años de Soledad", "Gabriel García Márquez"))
biblio.mostrar_libros()

# Salida esperada:
# 1. 1984 - George Orwell
# 2. Cien Años de Soledad - Gabriel García Márquez
```

