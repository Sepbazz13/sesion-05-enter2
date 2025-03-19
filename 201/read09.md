# Mitos y Verdades Analizados

## 1. "Usar `querySelector()` siempre devuelve una colección de nodos, incluso si selecciona uno solo."
- **Falso.** 
  - El método `querySelector()` siempre devuelve **el primer elemento** que coincida con el selector proporcionado, no una colección de nodos.
  - Si necesitas una colección de nodos, deberías usar `querySelectorAll()`.

---

## 2. "El DOM permite manipular estilos CSS directamente desde JavaScript usando propiedades específicas como `.style` y `.classList`."
- **Verdadero.**
  - Con `element.style` puedes aplicar estilos en línea directamente desde JavaScript.
  - Con `element.classList` puedes añadir, eliminar o alternar clases CSS, lo que resulta en cambios de estilo sin modificar directamente el CSS en línea.

---

## 3. "Una expresión regular (Regex) siempre devolverá el mismo resultado sin importar el contexto o idioma del texto que analice."
- **Falso.**
  - Las expresiones regulares no son sensibles al contexto o idioma, pero los datos que analizan **sí lo son**.
  - Por ejemplo, caracteres especiales o reglas de diferentes idiomas podrían afectar los resultados dependiendo del contenido procesado.

---

## 4. "Utilizar `querySelectorAll()` es menos eficiente que `getElementById` cuando se busca un único elemento por su ID."
- **Verdadero.**
  - `getElementById` está optimizado para buscar elementos por su ID y es más eficiente en rendimiento.
  - `querySelectorAll()` es más versátil, pero puede ser menos eficiente si solo necesitas buscar por ID.

---

## 5. "Todos los métodos del DOM devuelven elementos del mismo tipo, no existen diferencias entre ellos."
- **Falso.**
  - Diferentes métodos del DOM devuelven distintos tipos de resultados:
    - `getElementById` devuelve **un único elemento** o `null`.
    - `querySelectorAll` devuelve una **NodeList estática**.
    - Métodos como `getElementsByClassName` devuelven una **HTMLCollection viva**.

---

## 6. "`querySelectorAll()` permite seleccionar múltiples elementos y devuelve una lista estática (no viva) de nodos."
- **Verdadero.**
  - `querySelectorAll()` selecciona todos los elementos que coinciden con el selector y devuelve una **NodeList estática**.
  - Esto significa que no se actualiza automáticamente si los elementos cambian en el DOM.

---

## 7. "Las expresiones regulares (Regex) se pueden utilizar para transformar contenido de texto (Markdown a HTML, por ejemplo) sin necesidad de librerías externas."
- **Verdadero, con limitaciones.**
  - Las Regex pueden utilizarse para transformar contenido de texto como Markdown a HTML, pero implementar transformaciones completas y precisas puede ser complicado.
  - Usar una librería externa como **Marked.js** puede simplificar este proceso.

---

## 8. "Los cambios realizados en los nodos del DOM usando JavaScript son permanentes incluso después de refrescar la página."
- **Falso.**
  - Los cambios realizados en el DOM usando JavaScript son temporales y solo persisten mientras la página está cargada.
  - Al refrescar la página, el DOM se reconstruye desde el código fuente original.

---
