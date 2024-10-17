# Buenos días Café - Preentrega 3

## Mejoras Implementadas

### 1. SCSS por Pantalla
Cada HTML ahora tiene su propio archivo SCSS para organizar los estilos de manera modular:
- `index.html` -> `my_index.scss`
- `catalogo.html` -> `my_catalogo.scss`
- `carrito.html` -> `my_carrito.scss`
- `nosotros.html` -> `my_nosotros.scss`
- `contacto.html` -> `my_contacto.scss`

### 2. Mejoras en la UI
- Nuevas animaciones.
- Fuentes mejoradas.
- Mejores prácticas de diseño implementadas.

### 3. SEO Optimizado
Se agregaron metadatos en cada página para mejorar la visibilidad en los motores de búsqueda.

# Buenos días Café - Preentrega 3

## CEO Implementado

### 1. `index.html`

En el `<head>` se agregaron los siguientes metadatos para optimizar el SEO:

```html
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    
    <!-- Descripción corta de la página, aparece en búsquedas -->
    <meta name="description" content="Café de especialidad y productos artesanales desde Villa Rica, Perú." />
    
    <!-- Palabras clave que resumen el contenido de la página -->
    <meta name="keywords" content="café Villa Rica, café de especialidad, miel pura, chocolate artesanal, licor de café" />
    
    <!-- Título que describe mejor el contenido de la página -->
    <title>Café de Especialidad - Buenos días Café</title>
</head>

Para las imágenes, se añadieron descripciones alt para mejorar la accesibilidad y el SEO:
<img src="assets/imagenes/principal.jpg" alt="Café de especialidad desde Villa Rica" class="intro-image">
```
2. catalog.html 
```html
en el head:
<head>
    <title>Café de Especialidad - Productos Naturales | Buenos Días Café</title>
    <meta name="description" content="Descubre el mejor café de especialidad de Villa Rica y productos naturales como miel pura, chocolate artesanal y más. Compra online en Buenos Días Café.">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Otros metadatos -->
  </head>

se agrego un <main> </main> para la seccion produtcs

<main>
    <section id="products" class="container mt-4">
      <!-- Contenido de productos -->
    </section>
  </main>

Se agrego a las imagenes alt
```
3. carrito.html
```html
se mejoró el titulo y descripción 
<title>Carrito de Compras - Buenos días Café | Productos de Café y Miel</title>
<meta name="description"
    content="Revise su carrito de compras con productos de café de Villa Rica y miel pura. Finalice su compra y disfrute de nuestros productos de alta calidad.">

tambien se agregaron alt a las imagenes.
```
