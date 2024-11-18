# TAREA 5 - Lenguajes de marcas en la Web
### Juan Antonio Muñoz Godoy

### 1. ¿Qué es el lenguaje HTML?
HTML (Hypertext Markup Language) es el lenguaje de marcado utilizado para estructurar y presentar contenido en la web. HTML organiza el contenido en elementos como encabezados, párrafos, imágenes, enlaces y más, permitiendo que los navegadores interpreten y muestren esta información de manera adecuada en una página web. Es la base de cualquier sitio web y permite enlazar entre páginas mediante hipervínculos.

### 2. Relación de Tim Berners-Lee con HTML
Tim Berners-Lee es el inventor de la World Wide Web y el creador de HTML. En 1991, Berners-Lee desarrolló la primera versión de HTML para estructurar y vincular contenido en la web. Su trabajo fue fundamental para el desarrollo de la web tal como la conocemos hoy.

### 3. Distintas versiones del lenguaje HTML
HTML ha tenido varias versiones importantes a lo largo de los años:
- **HTML 1.0 (1991)**: La primera versión, creada por Tim Berners-Lee.
- **HTML 2.0 (1995)**: La primera versión estandarizada por el IETF.
- **HTML 3.2 (1997)**: Estándar con soporte para tablas, scripts y otros elementos visuales.
- **HTML 4.01 (1999)**: Introdujo mejoras en accesibilidad y separación de contenido y presentación.
- **HTML5 (2014)**: Versión moderna que añadió soporte para multimedia, gráficos y APIs avanzadas, sin necesidad de plugins externos.

### 4. ¿Qué es la W3C?
La **W3C** (World Wide Web Consortium) es una organización internacional que desarrolla y promueve estándares para la web, asegurando la interoperabilidad y el crecimiento de la web a nivel global. La W3C ha sido responsable de la estandarización de versiones de HTML y otros lenguajes y tecnologías web, como CSS y XML.

### 5. ¿Qué es el WHATWG?
El **WHATWG** (Web Hypertext Application Technology Working Group) es un grupo de trabajo que se formó en 2004 para desarrollar estándares abiertos de tecnologías web, en especial HTML. El WHATWG se centra en la creación de estándares dinámicos y en evolución constante, con el objetivo de adaptar HTML y otras tecnologías web a las necesidades actuales. A partir de 2019, el WHATWG mantiene HTML como un "Living Standard" (estándar vivo).

### 6. ¿Qué es un Living Standard?
Un **Living Standard** es un estándar en evolución constante que se actualiza regularmente en lugar de tener versiones fijas. Esto permite que el estándar se adapte rápidamente a las necesidades y tecnologías emergentes. HTML, bajo la administración del WHATWG, se considera un Living Standard, lo que significa que no tiene una versión específica y se modifica y mejora continuamente.

### 7. ¿Qué es el lenguaje XHTML?
**XHTML** (Extensible Hypertext Markup Language) es una reformulación de HTML basada en XML. Fue creado para imponer una estructura más estricta y una mayor consistencia en la sintaxis, a fin de hacer el código más predecible y compatible con otras aplicaciones y tecnologías XML. XHTML fue diseñado para mejorar la interoperabilidad y asegurar que las páginas fueran más estrictas y compatibles con estándares.

### 8. Distintas versiones del lenguaje XHTML
Las principales versiones de XHTML son:
- **XHTML 1.0 (2000)**: La primera versión, que es esencialmente HTML 4.01 con una sintaxis más estricta.
- **XHTML 1.1 (2001)**: Versión más modularizada y aún más estricta, eliminando algunos elementos presentes en XHTML 1.0.
- **XHTML 2.0** (en borrador): Un intento de ampliar las capacidades de XHTML, pero fue abandonado en 2009, en favor del desarrollo de HTML5.

### 9. Diferencias sintácticas y estructurales entre XHTML y HTML
Las diferencias principales entre **XHTML** y **HTML** incluyen:

- **Sintaxis más estricta en XHTML**:
  - Las etiquetas deben cerrarse correctamente en XHTML (por ejemplo, `<br />` en lugar de `<br>`).
  - Todas las etiquetas deben estar en minúsculas, ya que XML es sensible a mayúsculas y minúsculas.
  - Los atributos deben tener siempre valores entre comillas (por ejemplo, `class="header"`).
  
- **Estructura más estricta en XHTML**:
  - XHTML debe cumplir con la estructura XML bien formada. Por ejemplo, los elementos vacíos deben cerrarse explícitamente (como `<img src="image.jpg" />`).
  - Los documentos XHTML requieren una declaración de tipo de documento XML y deben comenzar con `<?xml version="1.0" encoding="UTF-8"?>`.
  
- **Compatibilidad**:
  - HTML es más flexible y tolerante a errores que XHTML, mientras que los navegadores tratan a XHTML como XML, por lo que es más estricto en su procesamiento.
  
En resumen, mientras que HTML es más permisivo, XHTML obliga a una escritura más precisa y estructurada, adecuada para entornos donde la interoperabilidad con XML es esencial.
