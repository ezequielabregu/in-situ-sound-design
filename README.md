# Mi Sitio Web con Quarto

Este es un sitio web simple de una página creado con Quarto markdown.

## Estructura del Proyecto

- `index.qmd` - Archivo principal del sitio web
- `_quarto.yml` - Configuración del proyecto Quarto
- `styles.css` - Estilos personalizados
- `_site/` - Directorio de salida (generado automáticamente)

## Cómo usar

1. **Instalar Quarto**: Descargar desde https://quarto.org/docs/get-started/
2. **Renderizar el sitio**: 
   ```bash
   quarto render
   ```
3. **Vista previa en vivo**:
   ```bash
   quarto preview
   ```

## Personalización

- Edita `index.qmd` para cambiar el contenido
- Modifica `styles.css` para personalizar el diseño
- Ajusta `_quarto.yml` para configurar el sitio

## Deployment

Puedes desplegar tu sitio en:
- GitHub Pages
- Netlify
- Vercel
- Tu propio servidor

Para GitHub Pages, simplemente habilita Pages en la configuración del repositorio y apunta a la carpeta `_site` o configura una GitHub Action.