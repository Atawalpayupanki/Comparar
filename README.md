# Sistema de Anotación de Noticias sobre China

Aplicación web para que voluntarios clasifiquen noticias relacionadas con China según tema e imagen del país.

## Uso

1. Abre el enlace de GitHub Pages
2. Introduce tu nombre o alias
3. Lee cada noticia y selecciona:
   - **Tema**: Categoría principal de la noticia
   - **Imagen de China**: Cómo se representa a China en la noticia
4. Al completar las 15 noticias, pulsa "Enviar resultados"

## Para desarrolladores

### Archivos
- `index.html` - Aplicación completa (HTML + CSS + JS)
- `noticias.json` - Base de datos de 50 noticias (25 ES + 25 ZH)

### Configuración de Formspree
Para recibir los resultados por email:
1. Crea una cuenta en [formspree.io](https://formspree.io)
2. Crea un nuevo formulario
3. Copia tu ID del formulario
4. Edita `index.html` y reemplaza `TU_ID_AQUÍ` en la línea:
   ```javascript
   const FORMSPREE_ENDPOINT = 'https://formspree.io/f/TU_ID_AQUÍ';
   ```

### Despliegue local
Simplemente abre `index.html` en cualquier navegador moderno.

## Tecnologías
- HTML5 + CSS3 + JavaScript vanilla
- Tailwind CSS (vía CDN)
- Formspree para envío de datos
