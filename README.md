# ejercicio_2

### main.py

```python
def calcular_letra_dni(dni):
    letras = "TRWAGMYFPDXBNJZSQVHLCKE"
    return letras[dni % 23]

if __name__ == "__main__":
    # Solicitar número de DNI al usuario
    dni = int(input("Introduce el número de DNI: "))
    letra = calcular_letra_dni(dni)
    print(f"La letra del DNI es: {letra}")
```

### Rama 1: `calculo_dni`

```python
def calcular_letra_dni(dni):
    letras = "TRWAGMYFPDXBNJZSQVHLCKE"
    return letras[dni % 23]

if __name__ == "__main__":
    # Solicitar número de DNI al usuario
    dni = int(input("Introduce el número de DNI: "))
    letra = calcular_letra_dni(dni)
    print(f"La letra del DNI es: {letra}")
```

### Rama 2: `funcion_dni`

```python
def calcular_letra_dni(dni):
    letras = "TRWAGMYFPDXBNJZSQVHLCKE"
    return letras[dni % 23]
```

### Rama 3: `main_dni`

```python
if __name__ == "__main__":
    # Solicitar número de DNI al usuario
    dni = int(input("Introduce el número de DNI: "))
    letra = calcular_letra_dni(dni)
    print(f"La letra del DNI es: {letra}")

def calcular_letra_dni(dni):
    letras = "TRWAGMYFPDXBNJZSQVHLCKE"
    return letras[dni % 23]
```


