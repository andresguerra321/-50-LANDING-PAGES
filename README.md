# Colección de Landing Pages

## Descripción del proyecto

Este repositorio contiene una colección de landing pages desarrolladas como práctica y mejora continua en diseño y maquetación web.
Cada landing page es independiente y está organizada en carpetas numeradas para mantener un orden progresivo.

## Estructura del proyecto

El repositorio está organizado en carpetas con numeración consecutiva (`1/`, `2/`, `3/`, hasta `50/`).

Además, en la raíz del proyecto se encuentra el archivo **`menu.html`**, el cual funciona como un menú interactivo que agrupa y enlaza a todas las landing pages disponibles, ofreciendo una navegación sencilla y visual.

Cada carpeta numerada contiene:
- `index.html`
- Carpeta `CSS/` (estilos)
- Carpeta `media/` (imágenes necesarias para el diseño)

> ⚠ **Importante:** Es necesario descargar la carpeta completa o el repositorio completo para que la landing funcione correctamente, ya que las imágenes y los estilos están vinculados mediante rutas relativas. Si solo se descarga el archivo `index.html`, la página no se visualizará correctamente.

## Instrucciones de uso

### Opción 1: Usar el Menú Principal (Recomendado)
1. Descargue o clone el repositorio completo.
2. Ingrese a la carpeta principal del repositorio.
3. Abra el archivo **`menu.html`** en su navegador web.
4. Seleccione cualquier tarjeta numérica para visualizar la landing page correspondiente.

### Opción 2: Vista Individual
1. Ingrese a la carpeta de la landing que desea visualizar (por ejemplo, `45`).
2. Abra el archivo `index.html` dentro de esa carpeta de forma manual en su navegador.

### Opción 3: Servidor Local
Para evitar posibles errores con rutas relativas (ideal para visualizar sin restricciones de CORS local):
1. Abra una terminal dentro de la carpeta principal del proyecto.
2. Ejecute el siguiente comando:
   ```bash
   python -m http.server 8000
   ```
3. Abra en el navegador:
   http://localhost:8000/menu.html 
   (O reemplace `menu.html` por `45/` si desea ir directamente a una landing).

## Notas importantes
- Cada landing funciona de manera independiente.
- Es obligatorio mantener la estructura de carpetas (raíz, CSS, media).
- No se debe modificar la numeración existente.
- Se recomienda verificar que las imágenes y estilos estén correctamente vinculados antes de subir cambios.

**Autor**: Andrés Felipe Guerra Correa
