# Respuestas a las afirmaciones

## 1. "Todos los lenguajes orientados a objetos soportan herencia múltiple por defecto."
- **Falso.** No todos los lenguajes orientados a objetos soportan herencia múltiple por defecto. Por ejemplo:
  - **Java**: No la soporta directamente, optando por interfaces como alternativa.
  - **C++**: Sí permite herencia múltiple, pero puede generar problemas como el "diamante de herencia".

---

## 2. "La Programación Orientada a Objetos permite organizar el código en entidades con responsabilidad clara."
- **Verdadero.** La POO organiza el código mediante clases y objetos, siguiendo principios como el de **Responsabilidad Única**, lo que facilita la modularidad, el mantenimiento y la reutilización.

---

## 3. "En JavaScript, usar funciones constructoras es obsoleto porque existen las clases desde ES6."
- **Parcialmente cierto.** 
  - Las **clases de ES6** ofrecen una sintaxis más clara y estructurada para definir constructores y herencia, pero las **funciones constructoras** siguen siendo válidas y funcionales.
  - En proyectos más antiguos o en entornos donde no se utiliza ES6, las funciones constructoras todavía se emplean.

---

## 4. "La abstracción implica eliminar cualquier detalle que no sea importante para la funcionalidad principal."
- **Verdadero.** La abstracción se enfoca en simplificar el diseño del programa al ocultar detalles innecesarios y exponer solo los aspectos relevantes para la funcionalidad principal.

---

## 5. "Para crear objetos usando funciones constructoras, es obligatorio usar el prototipo explícamente."
- **Falso.** No es obligatorio usar el prototipo explícitamente para crear objetos con funciones constructoras. Sin embargo:
  - Utilizar el **prototipo** es una buena práctica para compartir métodos entre instancias y optimizar el uso de memoria.

---

## 6. "La POO promueve la escalabilidad al agrupar datos y comportamiento en entidades lógicas."
- **Verdadero.** 
  - La POO combina datos y comportamientos en **clases u objetos**, lo que facilita la **escalabilidad** al permitir la expansión del código sin afectar su funcionalidad base.

---

## 7. "La palabra clave this en las funciones constructoras apunta a un objeto global, sin importar si se usa new."
- **Falso.**
  - Cuando se usa `new` con una función constructora, `this` apunta al nuevo objeto creado.
  - Si no se usa `new`:
    - En **modo estricto**, `this` será `undefined`.
    - En **modo no estricto**, `this` apuntará al objeto global (como `window` en navegadores).

---
