# ⚠️ Iconos Pendientes

Para que la PWA funcione correctamente, necesitas crear los siguientes iconos:

## Iconos Requeridos

1. **icon-192.png** - 192x192 píxeles
2. **icon-512.png** - 512x512 píxeles

## Cómo Crear los Iconos

### Opción 1: Online (Recomendado)

1. Ve a [Favicon.io](https://favicon.io/favicon-generator/)
2. Crea un ícono con:
   - Texto: "💧" o "AC" (tus iniciales)
   - Color de fondo: #667eea (morado/azul)
   - Color de texto: blanco
3. Descarga el paquete
4. Renombra los archivos a `icon-192.png` y `icon-512.png`
5. Cópialos a la raíz del proyecto

### Opción 2: Photoshop/GIMP

1. Crea una imagen cuadrada de 512x512px
2. Usa el color de fondo #667eea
3. Añade un ícono de gota de agua o texto
4. Guarda como `icon-512.png`
5. Redimensiona a 192x192px y guarda como `icon-192.png`

### Opción 3: Canva

1. Ve a [Canva.com](https://www.canva.com)
2. Crea un diseño de 512x512px
3. Usa plantillas de iconos de aplicación
4. Descarga en PNG
5. Crea ambos tamaños (192 y 512)

## Verificar que Funciona

1. Coloca los archivos `icon-192.png` y `icon-512.png` en la raíz del proyecto
2. Abre `index.html` en Chrome
3. Abre DevTools (F12) → Application → Manifest
4. Deberías ver los iconos cargados correctamente

## Nota

Por ahora, la aplicación funcionará sin iconos, pero no se podrá instalar como PWA hasta que los añadas.
