**Examen de Python**

**Instrucciones:**

- Lee cuidadosamente cada pregunta antes de responder.
- Escribe tu código en el espacio provisto.
- No modifiques el código proporcionado, a menos que se indique explícitamente.
- Asegúrate de seguir las convenciones de nomenclatura y las instrucciones dadas.
- Las funciones deben estar documentadas adecuadamente con docstrings.
- Considera manejar casos especiales y errores de manera apropiada.
- ¡Buena suerte!

---

**1. Funciones y Listas**

Escribe una función llamada `multiplicar_pares` que tome una lista de números como entrada y devuelva la multiplicación de todos los números pares en la lista. Si la lista está vacía, no contiene números pares o contiene solo un número par, la función debería devolver -1.

```python
def multiplicar_pares(lista):
    """
    Devuelve la multiplicación de todos los números pares en la lista.

    Args:
    - lista: Una lista de números.

    Returns:
    - La multiplicación de los números pares en la lista o -1 si la lista está vacía, no contiene números pares o contiene solo un número par.
    """
    # Escribe tu código aquí

# Ejemplo de uso:
nums = [1, 2, 3, 4, 5]
print(multiplicar_pares(nums))  # Debería imprimir 8
```

**2. Diccionarios**

Dado el siguiente diccionario que representa el inventario de una tienda:

```python
inventario = {
    "manzanas": {"cantidad": 50, "precio_unitario": 2},
    "plátanos": {"cantidad": 30, "precio_unitario": 1.5},
    "uvas": {"cantidad": 40, "precio_unitario": 3},
    "peras": {"cantidad": 25, "precio_unitario": 2.5}
}
```

Escribe una función llamada `actualizar_inventario` que tome el inventario actual, un artículo, una cantidad y un precio, y actualice el inventario con la cantidad y el precio especificados para ese artículo. Si el artículo no existe en el inventario, debe ser agregado. Además, si el precio especificado es negativo o la cantidad es negativa o cero, no se realizará ninguna actualización y la función devolverá False.

```python
def actualizar_inventario(inventario, articulo, cantidad, precio):
    """
    Actualiza el inventario con la cantidad y el precio especificados para el artículo dado.

    Si el artículo no existe, lo agrega al inventario.

    Args:
    - inventario: Un diccionario que representa el inventario de la tienda.
    - articulo: El artículo que se va a actualizar o agregar.
    - cantidad: La cantidad que se va a agregar al artículo.
    - precio: El precio unitario del artículo.

    Returns:
    - True si la actualización se realizó con éxito, False si no se realizó ninguna actualización.
    """
    # Escribe tu código aquí

# Ejemplo de uso:
print(inventario)
print(actualizar_inventario(inventario, "manzanas", 20, 2.25))  # Debería imprimir True
print(inventario)  # Debería imprimir {'manzanas': {'cantidad': 70, 'precio_unitario': 2.25}, 'plátanos': {'cantidad': 30, 'precio_unitario': 1.5}, 'uvas': {'cantidad': 40, 'precio_unitario': 3}, 'peras': {'cantidad': 25, 'precio_unitario': 2.5}}
```

**3. Manipulación de Archivos**

Supongamos que tienes un archivo llamado "nombres.txt" que contiene una lista de nombres, uno por línea. Escribe una función llamada `contar_nombres` que tome el nombre del archivo como entrada y devuelva un diccionario donde las claves sean los nombres y los valores sean la cantidad de veces que aparece cada nombre en el archivo. Además, excluye los nombres que contienen números y convierte todos los nombres a minúsculas antes de contarlos.

```python
def contar_nombres(nombre_archivo):
    """
    Cuenta la cantidad de veces que aparece cada nombre (sin números) en el archivo.

    Args:
    - nombre_archivo: El nombre del archivo que contiene la lista de nombres.

    Returns:
    - Un diccionario donde las claves son los nombres (sin números y en minúsculas) y los valores son la cantidad de veces que aparece cada nombre.
    """
    # Escribe tu código aquí

# Ejemplo de uso:
print(contar_nombres("nombres.txt"))
```
