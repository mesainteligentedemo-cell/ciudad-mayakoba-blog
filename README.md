# 🏝️ Ciudad Mayakoba - Blog

Blog estático para Ciudad Mayakoba, Riviera Maya.

## Características

✨ **Bilingüe** — Español / Inglés con toggle  
💱 **Convertidor de Moneda** — USD ↔ MXN en vivo  
📱 **Responsive** — Mobile, tablet, desktop  
🎨 **Luxury Design** — Dorado + Negro + Blanco  
📝 **Contenido Modificable** — Artículos, imágenes, textos  

## Stack

- HTML5 puro
- CSS3 (variables, grid, flexbox)
- Vanilla JavaScript (sin dependencias)

## Deploy

**Vercel:** [ciudad-mayakoba-blog.vercel.app](https://ciudad-mayakoba-blog.vercel.app)

## Local Development

```bash
npm run dev
# Abre http://localhost:8080
```

## Modificar Contenido

Editar `index.html` → buscar `const blogData`:

```javascript
const blogData = {
    es: [
        {
            id: 1,
            title: "Título artículo",
            excerpt: "Descripción corta",
            date: "Fecha aquí",
            image: "URL imagen",
            content: "<h2>Título</h2><p>Contenido HTML</p>"
        }
    ]
}
```

## Colores Personalizables

En `<style>` → `:root`:
```css
--primary-color: #1a1a1a;    /* Negro */
--secondary-color: #ffffff;  /* Blanco */
--accent-color: #d4af37;     /* Dorado */
--text-color: #333333;
--light-bg: #f5f5f5;
```

---

**Hecho con ❤️ por Victor IA**