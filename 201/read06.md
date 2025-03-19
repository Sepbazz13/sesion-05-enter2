# Respuestas a las preguntas

## 1. ¿Qué diferencias fundamentales encuentras entre resolver un problema con programación imperativa y hacerlo con programación funcional?

- **Programación Imperativa**: Se centra en el "cómo" se debe realizar una tarea. Describe una secuencia de pasos o instrucciones para modificar el estado del programa (ej., uso de bucles y asignaciones variables).
- **Programación Funcional**: Se enfoca en el "qué" se quiere lograr. Usa funciones puras y evita el estado mutable, lo que promueve un código más declarativo y predecible.
- Diferencia clave: La imperativa modifica estados y variables, mientras que la funcional favorece la inmutabilidad y composiciones funcionales.

---

## 2. ¿En qué situaciones específicas crees que es más ventajoso aplicar funciones puras, y en cuáles no lo sería?

- **Ventajoso**:
  - Cuando buscas consistencia y predecibilidad en los resultados (sin efectos secundarios).
  - Para aplicaciones donde el debugging es crítico, ya que las funciones puras son fáciles de probar.
  - En tareas que involucran cálculos matemáticos o procesamiento de datos.

- **No ventajoso**:
  - En programas que requieren interacción constante con el estado mutable (como manejar interfaces gráficas o trabajar con bases de datos).
  - Situaciones donde se priorice el rendimiento extremo y el estilo funcional introduzca una sobrecarga innecesaria.

---

## 3. ¿Qué rol juegan las funciones de orden superior como `map()`, `filter()` y `find()` en la calidad y legibilidad del código?

- Estas funciones hacen el código **más legible y declarativo**, ya que abstraen operaciones comunes como transformación, filtrado o búsqueda, eliminando la necesidad de bucles explícitos.
- **Calidad del código**:
  - Reducen el riesgo de errores al encapsular la lógica repetitiva.
  - Fomentan la reusabilidad y la composición de funciones pequeñas y enfocadas.

---

## 4. ¿Por qué la programación funcional facilita las pruebas unitarias y el debugging?

- **Funciones puras** no dependen de variables externas ni producen efectos secundarios, lo que simplifica las pruebas.
- La inmutabilidad elimina problemas relacionados con el cambio de estado, haciendo más fáciles de detectar los errores.
- Al favorecerse funciones pequeñas y reutilizables, se puede probar cada componente de manera aislada.

---

## 5. ¿Cómo puedes integrar efectivamente el paradigma funcional en proyectos que originalmente fueron construidos con un enfoque imperativo?

- **Paso a paso**:
  1. Identifica y refactoriza pequeñas partes del código que puedan ser reescritas usando funciones puras.
  2. Incorpora funciones de orden superior (`map()`, `filter()`, etc.) para operaciones comunes.
  3. Introduce librerías de programación funcional como Lodash (JavaScript) o Ramda.
- **Recomendación**: Mantén un equilibrio entre ambos paradigmas. La programación funcional puede coexistir con la imperativa, aprovechando las ventajas de cada enfoque.

---
