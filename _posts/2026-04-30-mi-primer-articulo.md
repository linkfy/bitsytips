---
layout: post
title: "Guía de Markdown para Programadores"
date: 2026-04-30 19:00:00 +0400
categories: programacion
image: "https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=800&h=400&fit=crop"
---

Bienvenido a mi primer artículo sobre los elementos de Markdown más útiles para escribir sobre programación. En este artículo aprenderás cómo estructurar y presentar tu código de manera clara y profesional.

## Títulos y Estructura

Los títulos son fundamentales para organizar tu contenido. Utiliza `#` para crear diferentes niveles:

```markdown
# Título 1 (h1)
## Título 2 (h2)
### Título 3 (h3)
```

## Listas

Las listas te ayudan a organizar información de manera clara:

### Listas sin orden
- Elemento uno
- Elemento dos
  - Sub-elemento 2.1
  - Sub-elemento 2.2
- Elemento tres

### Listas ordenadas
1. Primer paso
2. Segundo paso
3. Tercer paso

## Código Inline

Para hacer referencia a código dentro del texto, usa backticks: `console.log()`, `function`, `const`, `return`.

## Bloques de Código con Highlighting

### JavaScript
```javascript
function factorial(n) {
  if (n <= 1) return 1;
  return n * factorial(n - 1);
}

console.log(factorial(5)); // Resultado: 120
```

### Python
```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

print(fibonacci(10))  # Resultado: 55
```

### HTML
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi Página</title>
</head>
<body>
    <h1>¡Hola Mundo!</h1>
    <p>Este es un ejemplo básico de HTML</p>
</body>
</html>
```

### CSS
```css
/* Estilos personalizados */
.contenedor {
    max-width: 860px;
    margin: 0 auto;
    padding: 20px;
    background: #1b1d20;
}

.contenedor:hover {
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
```

### Bash
```bash
#!/bin/bash

# Script para listar archivos
echo "Archivos en el directorio:"
ls -la

# Variables
nombre="Programador"
echo "Hola, $nombre"
```

## Tablas

Las tablas son excelentes para comparar datos:

| Lenguaje | Tipo | Ejemplo |
|----------|------|---------|
| JavaScript | Dinámico | `const x = 10;` |
| Python | Dinámico | `x = 10` |
| Java | Estático | `int x = 10;` |
| Rust | Estático | `let x: i32 = 10;` |

## Imágenes

Las imágenes son excelentes para visualizar conceptos y mejorar la presentación de tu contenido. Puedes usar imágenes tanto locales como externas:

![Ejemplo de imagen - Pantalla con código](https://images.unsplash.com/photo-1633356122544-f134324ef6db?w=800&h=400&fit=crop)

También puedes usar figuras con descripciones:

<figure>
  <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=600&h=300&fit=crop" alt="Editor de código">
  <figcaption>Una figura con descripción: Un editor de código bien configurado es esencial para la productividad</figcaption>
</figure>

## Citas

> "La programación es como la magia: a veces funciona, a veces necesitas un debugger más grande."
>
> — Sabiduría anónima de desarrolladores

> **Tip importante:** Siempre escribe código legible. Tu yo del futuro te lo agradecerá.

## Énfasis

Puedes hacer **texto en negrita** o *texto en cursiva*. También puedes combinar: ***texto en negrita y cursiva***.

## Enlaces

Aquí puedes [enlazar a otros sitios](https://www.google.com) o [volver al Blog]({{ site.baseurl }}/).

## Conclusión

Markdown es una herramienta poderosa para documentar tu código y compartir conocimiento. La combinación de estructura clara, ejemplos de código bien formateados y explicaciones concisas hace que tus artículos sean más profesionales y fáciles de entender.

¡Espero que este artículo te haya sido útil para entender cómo presentar tus proyectos de programación!