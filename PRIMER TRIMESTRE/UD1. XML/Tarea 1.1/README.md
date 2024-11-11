# Tarea 1.1 - Lenguaje de marcas
### Juan Antonio Muñoz Godoy
---
## **1. Indica qué es un lenguaje de marcas.**

Un lenguaje de marcas es un sistema de notación que utiliza etiquetas o marcas para estructurar y presentar información. Estas etiquetas indican cómo se debe interpretar el contenido, facilitando la organización y el formato de los datos. Los lenguajes de marcas más conocidos son HTML y XML. 

En general, permiten separar el contenido de la presentación, lo que hace más fácil modificar o reutilizar la información en diferentes contextos.

## **2. Características generales de los lenguajes de marcas.**

Los lenguajes de marcas tienen varias características generales que los definen:

- **Estructuración del contenido**: Utilizan etiquetas para organizar y estructurar datos, lo que facilita su interpretación.

- **Legibilidad**: Las etiquetas suelen ser descriptivas, lo que ayuda a los humanos a entender el contenido y su propósito.

- **Separación de contenido y presentación:** Permiten separar la estructura del contenido (como texto, imágenes, etc.) de su presentación visual, lo que facilita cambios sin afectar el contenido.

- **Jerarquía**: Permiten la creación de estructuras jerárquicas, donde se pueden anidar etiquetas dentro de otras, reflejando relaciones entre los datos.

- **Flexibilidad**: Muchos lenguajes de marcas son extensibles, lo que significa que puedes crear tus propias etiquetas para satisfacer necesidades específicas.

- **Interoperabilidad**: Facilitan el intercambio de datos entre diferentes sistemas y plataformas, ya que son estándares abiertos en muchos casos.

- **Validación**: Muchos lenguajes de marcas permiten la validación de documentos, asegurando que cumplen con ciertas reglas o esquemas.

- **Soporte para metadatos**: Permiten incluir información adicional sobre los datos (metadatos), lo que mejora la búsqueda y el manejo de la información.

## **3. Clasifica los lenguajes de marcas e identifica los más relevantes.**

Los lenguajes de marcas se pueden clasificar en diferentes categorías según su propósito y características.

**1. Lenguajes de marcas para estructuración de documentos**


- **HTML**: Utilizado para crear y estructurar contenido en la web.
- **Markdown**: Un lenguaje ligero para formatear texto que se convierte fácilmente en HTML.

**2. Lenguajes de marcas para almacenamiento y transporte de datos**

- **XML**: Utilizado para almacenar y transportar datos de manera estructurada. Es flexible y se puede personalizar con etiquetas propias.
- **JSON**: Aunque no es un lenguaje de marcas en el sentido tradicional, se utiliza para representar datos en una estructura similar a la de objetos, especialmente en aplicaciones web.

**3. Lenguajes de marcas para presentación**

- **XHTML**: Una versión más estricta de HTML que combina HTML y XML.
- **XSL**: Utilizado para transformar y presentar documentos XML.

**4. Lenguajes de marcas para datos semánticos**

- **RDF**: Utilizado para describir recursos en la web y sus relaciones.
- **SVG**: Utilizado para crear gráficos vectoriales y puede ser incrustado en documentos HTML.

**5. Lenguajes de marcas para diseño web y aplicaciones**
- **CSS**: Aunque no es un lenguaje de marcas per se, se utiliza en conjunto con HTML para dar estilo y presentación a los documentos web.

**6. Lenguajes de marcas específicos de dominio**
- **LaTeX**: Utilizado principalmente en la academia para la preparación de documentos científicos y técnicos.
- **TeX**: Un sistema de tipografía que se basa en un lenguaje de marcas.

**Más Relevantes:**
- HTML: Fundamental para la web.
- XML: Esencial para el intercambio de datos entre aplicaciones.
- JSON: Muy popular en desarrollo web y APIs.
- Markdown: Ampliamente utilizado para documentaciones y blogs.
- CSS: Crucial para la presentación en la web.

## **5. Inserta un trozo de código de cada uno de los lenguajes de marcas que se indican a continuación. Añadir a cada trozo de código un pequeño resumen sobre su estructura y la aplicación asociada que los procesa:**

-  **HTML**: 
```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo HTML</title>
</head>
<body>
    <h1>Bienvenido</h1>
    <p>Este es un ejemplo sencillo de HTML.</p>
    <a href="mailto:ejemplo@correo.com">Contáctame</a>
</body>
</html>
```

- **iCalendar**: 

```
BEGIN:VEVENT
UID:1234567890@example.com
DTSTAMP:20231002T120000Z
DTSTART:20231015T090000Z
DTEND:20231015T100000Z
SUMMARY:Reunión de equipo
DESCRIPTION:Reunión semanal del equipo para discutir proyectos.
LOCATION:Oficina central
STATUS:CONFIRMED
END:VEVENT
```

- **vCard** 

```  
BEGIN:VCARD
VERSION:3.0
FN:Juan Pérez
N:Pérez;Juan;;;
ORG:Empresa Ejemplo
TITLE:Desarrollador de Software
TEL;TYPE=WORK,VOICE:(123) 456-7890
TEL;TYPE=CELL,VOICE:(098) 765-4321
EMAIL:j.perez@ejemplo.com
ADR;TYPE=WORK:;;123 Calle Principal;Ciudad;Estado;Código Postal;País
URL:http://www.ejemplo.com
END:VCARD
```

- **KML**
  
<kml xmlns="http://www.opengis.net/kml/2.2">
  <Document>
    <name>Ejemplo de KML</name>
    <description>Un simple archivo KML con un marcador.</description>

    <Placemark>
      <name>Punto de Interés</name>
      <description>Descripción del punto de interés.</description>
      <Point>
        <coordinates>-74.0060,40.7128,0</coordinates>
      </Point>
    </Placemark>
    
    <Style id="estiloMarcador">
      <IconStyle>
        <Icon>
          <href>http://example.com/icon.png</href>
        </Icon>
      </IconStyle>
    </Style>

  </Document>
</kml>

- **RSS**

<?xml version="1.0" encoding="UTF-8"?>
<rss version="2.0">
  <channel>
    <title>Ejemplo de Feed RSS</title>
    <link>http://www.ejemplo.com</link>
    <description>Este es un feed RSS de ejemplo para ilustrar su uso.</description>
    <language>es-es</language>
    
    <item>
      <title>Primera noticia</title>
      <link>http://www.ejemplo.com/noticia1</link>
      <description>Descripción de la primera noticia.</description>
      <pubDate>Mon, 02 Oct 2023 12:00:00 GMT</pubDate>
      <guid>http://www.ejemplo.com/noticia1</guid>
    </item>

    <item>
      <title>Segunda noticia</title>
      <link>http://www.ejemplo.com/noticia2</link>
      <description>Descripción de la segunda noticia.</description>
      <pubDate>Tue, 03 Oct 2023 12:00:00 GMT</pubDate>
      <guid>http://www.ejemplo.com/noticia2</guid>
    </item>

  </channel>
</rss>

