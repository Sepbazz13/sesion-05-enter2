# Mitos y Verdades Analizados

## 1. "El `prototype` de una función y el `__proto__` de un objeto son exactamente lo mismo."
- **Falso.** 
  - El `prototype` es una propiedad de las funciones constructoras que define el prototipo de las instancias que se crean a partir de ellas.
  - El `__proto__` es una propiedad de los objetos que apunta al prototipo del cual heredan.
  - Aunque están relacionados, no son lo mismo; el `__proto__` conecta al objeto con la cadena de prototipos.

---

## 2. "La cadena de prototipos permite la reutilización de métodos y propiedades, lo cual es esencial para la herencia en JavaScript."
- **Verdadero.**
  - La cadena de prototipos permite que los objetos hereden métodos y propiedades de otros objetos a través de su prototipo.
  - Este mecanismo es fundamental para implementar la herencia en JavaScript, promoviendo la reutilización y la reducción de redundancias.

---

## 3. "Las funciones constructoras son obsoletas y no se usan en el desarrollo moderno de JavaScript."
- **Parcialmente cierto.**
  - Desde la introducción de las clases en ES6, las funciones constructoras han caído en desuso debido a que las clases son más claras y expresivas.
  - Sin embargo, no son técnicamente obsoletas y aún pueden encontrarse en proyectos antiguos o con enfoques específicos.

---

## 4. "Manipular correctamente `__proto__` puede mejorar la reutilización de código, pero su uso inadecuado puede generar problemas de seguridad y mantenimiento."
- **Verdadero.**
  - Manipular `__proto__` puede ser útil en algunos casos para ajustar la herencia prototípica dinámicamente, pero es una práctica generalmente desaconsejada.
  - El uso incorrecto puede introducir vulnerabilidades de seguridad, dificultades para depurar el código y problemas de rendimiento.

---

## 5. "Modificar el `prototype` de una función siempre afecta a todas las instancias existentes sin excepción."
- **Falso.**
  - Si el `prototype` se modifica después de haber creado instancias, estas no se verán afectadas automáticamente.
  - Las nuevas propiedades o métodos añadidos al `prototype` estarán disponibles solo para las futuras instancias creadas.

---
