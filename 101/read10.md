### ¿Qué es “Control Flow” (Control de Flujo)?
El **Control de Flujo** se refiere a la forma en que un programa ejecuta sus instrucciones. Determina el orden en que se ejecutan las sentencias, permitiendo la toma de decisiones (con estructuras como `if`, `else`, `switch`), la repetición de código (con bucles como `for`, `while`, `do-while`) y la gestión de excepciones (con `try`, `catch`, `finally`).

---

### ¿Qué es una “function” (Función) de JavaScript?
Una **función** en JavaScript es un bloque de código reutilizable que realiza una tarea específica. Se define con la palabra clave `function`, seguida de un nombre, parámetros (opcionales) y un cuerpo de código entre llaves `{}`. Las funciones pueden devolver un valor usando `return`.

Ejemplo:
```javascript
function sumar(a, b) {
    return a + b;
}
```

### ¿Cuántas veces se ejecutará un bucle “while”?

let contador = 0;
while (contador < 5) {
    console.log(contador);
    contador++;
}
// Este bucle se ejecutará 5 veces.
### ¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?

let frutas = ["manzana", "banana"];
frutas.push("naranja"); // Agrega "naranja" al final del array
console.log(frutas); // ["manzana", "banana", "naranja"]