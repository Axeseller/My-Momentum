# Momentum Blog - Instrucciones de Uso

## 📋 Descripción del Proyecto

Este es tu blog personal "Momentum" para documentar tu experiencia en Prepa Tec. El diseño sigue un estilo escandinavo moderno: limpio, minimalista y elegante.

## 🗂️ Estructura del Proyecto

```
Mi momentum/
├── index.html              # Página principal
├── styles/                 # Estilos CSS modulares
│   ├── main.css           # Estilos base y variables
│   ├── header.css         # Navegación
│   ├── hero.css           # Sección hero
│   ├── autobiography.css  # Sección biografía
│   ├── top10.css          # Sección top 10
│   └── footer.css         # Footer
├── images/                 # Carpeta para imágenes
└── INSTRUCTIONS.md         # Este archivo
```

## 🎨 Diseño y Estilo

### Características del Diseño:
- **Estilo Escandinavo Moderno**: Minimalista, limpio, con mucho espacio en blanco
- **Tipografía**: 
  - Títulos: Playfair Display (elegante serif)
  - Texto: Inter (moderna sans-serif)
- **Colores**:
  - Primario: #2C3E50 (azul oscuro)
  - Acento: #3498DB (azul claro)
  - Fondo: #FFFFFF y #F8F9FA
- **Responsive**: Se adapta a móviles, tablets y escritorio

## 📝 Cómo Personalizar Tu Blog

### 1. Sección Hero (26 de enero)

**Ubicación**: Líneas 36-58 en `index.html`

**Qué hacer**:
1. Reemplaza el texto en la clase `.hero-description` con el significado de Momentum para ti
2. Agrega tu imagen principal en `images/hero-image.jpg`

```html
<div class="hero-description">
    <p>
        Escribe aquí qué representa Momentum para ti...
    </p>
</div>
```

### 2. Sección Autobiografía (29 de enero)

**Ubicación**: Líneas 69-115 en `index.html`

**Qué hacer**:
1. Responde las preguntas en los tres bloques de texto:
   - ¿Cómo eras antes de Prepa?
   - Tus pasiones y hobbies
   - Fortalezas y emociones

2. Agrega tus fotos:
   - `images/childhood-1.jpg` - Primera infancia
   - `images/childhood-2.jpg` - Primaria
   - `images/childhood-3.jpg` - Secundaria

**Ejemplo**:
```html
<div class="text-block">
    <h3>¿Cómo era antes de Prepa?</h3>
    <p>
        Escribe tu historia aquí...
    </p>
</div>
```

### 3. Sección Top 10 Momentos (29 enero - 3 febrero)

**Ubicación**: Líneas 121-270 en `index.html`

**Qué hacer**:
Para cada uno de los 10 momentos:

1. Agrega la imagen: `images/moment-1.jpg` hasta `moment-10.jpg`
2. Escribe el título del momento
3. Describe el momento con detalle
4. Especifica la categoría

**Categorías sugeridas**:
- Deportes
- Cultura
- Académico
- Liderazgo
- Proyecto
- Internacional
- Emprendimiento
- Reconocimiento
- Viaje
- Amistad

**Ejemplo**:
```html
<article class="moment-card">
    <div class="moment-number">01</div>
    <div class="moment-image">
        <img src="images/moment-1.jpg" alt="Momento 1">
    </div>
    <div class="moment-content">
        <h3 class="moment-title">Campeonato de Fútbol 2024</h3>
        <p class="moment-description">
            Este fue uno de los momentos más emocionantes cuando...
        </p>
        <span class="moment-category">Deportes</span>
    </div>
</article>
```

## 📸 Manejo de Imágenes

### Nombres de Archivos Requeridos:
```
images/
├── hero-image.jpg          # Imagen principal
├── childhood-1.jpg         # Foto infancia
├── childhood-2.jpg         # Foto primaria
├── childhood-3.jpg         # Foto secundaria
└── moment-1.jpg a moment-10.jpg  # 10 momentos
```

### Recomendaciones:
- **Formato**: JPG o PNG
- **Resolución**: Mínimo 1920x1080px
- **Tamaño**: Máximo 2MB por imagen
- **Orientación**: 
  - Hero: Horizontal (4:3)
  - Biografía: Vertical (3:4)
  - Momentos: Horizontal o cuadrada

### ⚠️ IMPORTANTE:
- NO incluir bebidas alcohólicas
- NO incluir vapes o cigarrillos
- Seguir el reglamento escolar
- Usar fotos apropiadas y respetuosas

## 🚀 Cómo Ver Tu Blog

### Opción 1: Abrir directamente
1. Ve a la carpeta del proyecto
2. Doble clic en `index.html`
3. Se abrirá en tu navegador

### Opción 2: Con un servidor local (recomendado)
```bash
# Si tienes Python instalado:
cd "/home/axelmeiners/Documents/Mi momentum"
python3 -m http.server 8000

# Luego abre en tu navegador:
# http://localhost:8000
```

### Opción 3: Con VS Code Live Server
1. Instala la extensión "Live Server"
2. Click derecho en `index.html`
3. Selecciona "Open with Live Server"

## 🎨 Personalización Avanzada

### Cambiar Colores

Edita las variables en `styles/main.css`:

```css
:root {
    --color-primary: #2C3E50;    /* Color principal */
    --color-accent: #3498DB;     /* Color de acento */
    --color-bg: #FFFFFF;         /* Fondo */
}
```

### Cambiar Fuentes

Las fuentes se cargan desde Google Fonts. Para cambiar:

1. Ve a [Google Fonts](https://fonts.google.com/)
2. Elige tus fuentes
3. Reemplaza el link en `index.html` (línea 16)
4. Actualiza las variables en `styles/main.css`

### Ajustar Espaciado

Modifica las variables de espaciado en `styles/main.css`:

```css
:root {
    --spacing-sm: 1rem;
    --spacing-md: 2rem;
    --spacing-lg: 4rem;
    --spacing-xl: 6rem;
}
```

## 📱 Responsive Design

El sitio es completamente responsive y se verá bien en:
- 📱 Móviles (320px - 480px)
- 📱 Tablets (481px - 768px)
- 💻 Laptops (769px - 1024px)
- 🖥️ Desktop (1025px+)

## ✅ Checklist de Entrega

### 26 de enero:
- [ ] Título y descripción de Momentum
- [ ] Imagen hero agregada

### 29 de enero:
- [ ] Autobiografía completa
- [ ] 3 fotos de diferentes edades agregadas

### 29 enero - 3 febrero:
- [ ] 10 momentos documentados
- [ ] 10 imágenes agregadas
- [ ] Descripciones detalladas
- [ ] Categorías asignadas

### Pre-entrega:
- [ ] Todas las imágenes cumplen con el reglamento
- [ ] Todos los textos están completos
- [ ] El sitio se ve bien en móvil y escritorio
- [ ] No hay errores de ortografía

## 💡 Tips Finales

1. **Escribe con honestidad**: Tu historia es única, hazla brillar
2. **Usa buenas fotos**: Las imágenes hacen gran diferencia
3. **Sé específico**: Da detalles en las descripciones
4. **Revisa ortografía**: Usa un corrector antes de entregar
5. **Prueba en móvil**: Muchos verán tu blog desde el teléfono
6. **Guarda copias**: Haz backup de tus imágenes y archivos

## 🆘 Solución de Problemas

### Las imágenes no se ven:
- Verifica que los nombres coincidan exactamente
- Asegúrate de que estén en la carpeta `images/`
- Revisa que la extensión sea `.jpg` o `.png`

### El diseño se ve raro:
- Limpia el caché del navegador (Ctrl+Shift+R)
- Verifica que todos los archivos CSS estén enlazados
- Revisa la consola del navegador (F12)

### El texto no cabe:
- Reduce el texto o divídelo en párrafos
- Ajusta el tamaño de fuente en el CSS
- Considera hacer el texto más conciso

## 📞 Contacto

Si necesitas ayuda adicional:
- Revisa este archivo completo
- Consulta los comentarios en el código HTML
- Pide ayuda a tu profesor o compañeros

---

**¡Éxito con tu proyecto Momentum! 🚀**
