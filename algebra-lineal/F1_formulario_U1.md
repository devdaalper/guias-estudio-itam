# Formulario activo — Álgebra · U1 (Sistemas y Gauss-Jordan)

> **Memoria total:** en el examen NO hay formulario. Esto es para *repasar y memorizar con la práctica*, no para usar en el examen. Cada ficha: enunciado · por qué (deriva la idea) · drill (recuérdala a ciegas).

### 1. Operaciones elementales de renglón (las 3)
- Intercambiar dos renglones · multiplicar un renglón por un escalar ≠ 0 · sumar a un renglón un múltiplo de otro.
- **Por qué:** ninguna cambia el conjunto de soluciones (son reversibles). Multiplicar por 0 NO se vale (borra información); las columnas no se tocan.
- **Drill:** enúncialas sin ver.

### 2. Forma escalonada reducida (RREF) — cuándo una matriz “ya terminó”
- Cada pivote = 1, es el único distinto de cero en su columna, está a la derecha del pivote de arriba; los renglones de ceros van al fondo.
- **Por qué:** es la forma canónica; desde ella se leen las soluciones sin más cuentas.
- **Drill:** dibuja una matriz 2×3 en RREF y otra que NO lo esté, y di por qué.

### 3. Criterio de consistencia (leer el tipo de solución)
- **Inconsistente (ninguna):** aparece un renglón [0 … 0 | c] con c ≠ 0.
- **Única:** toda variable es pivote (no hay variables libres).
- **Infinitas:** hay al menos una variable libre (columna sin pivote).
- **Por qué:** cada caso sale de leer directamente la RREF.
- **Drill:** para cada caso, escribe una matriz 2×3 de ejemplo de memoria.

### 4. Variable libre
- Columna sin pivote → su variable es libre → se vuelve parámetro (t) y genera infinitas soluciones.
- **Drill:** en x − 2y = 1 (con y libre), escribe la solución general en términos de t.
