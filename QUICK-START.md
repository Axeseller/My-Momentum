# 🚀 Quick Start Guide - Momentum Blog

## 3 Pasos Simples para Empezar

### 📸 Paso 1: Agregar Imágenes (5 minutos)

Coloca tus fotos en la carpeta `images/` con estos nombres exactos:

```
images/
├── hero-image.jpg           # Tu foto principal de Prepa Tec
├── childhood-1.jpg          # Foto de infancia
├── childhood-2.jpg          # Foto de primaria  
├── childhood-3.jpg          # Foto de secundaria
├── moment-1.jpg            # Primer momento top
├── moment-2.jpg            # Segundo momento
... (hasta moment-10.jpg)
```

**💡 Tip**: Renombra tus fotos antes de copiarlas

---

### ✍️ Paso 2: Editar Contenido (20 minutos)

Abre `index.html` y busca los comentarios `<!-- INSTRUCCIÓN: -->`:

#### A. Hero Section (línea ~45)
```html
<p>
    Escribe qué significa Momentum para ti...
</p>
```

#### B. Autobiografía (líneas ~85, ~95, ~105)
```html
<p>
    Escribe sobre tu vida antes de Prepa...
</p>
```

#### C. Top 10 Momentos (líneas ~135+)
Para cada momento:
- Cambia `<h3 class="moment-title">` con el título
- Cambia `<p class="moment-description">` con la descripción
- Cambia `<span class="moment-category">` con la categoría

---

### 👀 Paso 3: Ver Tu Blog (1 minuto)

**Opción Simple**: 
- Doble clic en `index.html` ✨

**Opción con Servidor**:
```bash
cd "/home/axelmeiners/Documents/Mi momentum"
python3 -m http.server 8000
```
Luego abre: `http://localhost:8000`

---

## 📅 Calendario de Entregas

| Fecha | Tarea | Estado |
|-------|-------|--------|
| 26 enero | Hero + Imagen | ⏳ |
| 29 enero | Autobiografía + Fotos | ⏳ |
| 29 ene - 3 feb | Top 10 Momentos | ⏳ |

---

## ⚡ Atajos Útiles

### Encontrar y Reemplazar Rápido

En tu editor de código (VS Code, etc):
- `Ctrl+F` = Buscar
- `Ctrl+H` = Reemplazar

Busca: `<!-- INSTRUCCIÓN:` para encontrar todas las secciones a editar

---

## 🎨 Personalización Rápida de Colores

Archivo: `styles/main.css` (líneas 8-13)

```css
--color-primary: #2C3E50;    /* Azul oscuro → Cambia aquí */
--color-accent: #3498DB;     /* Azul claro → Cambia aquí */
```

**Colores sugeridos**:
- Azul: `#3498DB`
- Verde: `#27AE60`
- Morado: `#9B59B6`
- Rojo: `#E74C3C`
- Naranja: `#E67E22`

---

## ✅ Checklist Rápida

Antes de entregar, verifica:

- [ ] Todas las imágenes cargadas
- [ ] Todos los textos completados
- [ ] Sin "Lorem ipsum" o texto placeholder
- [ ] Fotos cumplen con reglamento
- [ ] Se ve bien en móvil
- [ ] Sin errores de ortografía

---

## 🆘 Problemas Comunes

### ❌ "La imagen no se ve"
✅ **Solución**: 
- Verifica el nombre exacto del archivo
- Debe estar en carpeta `images/`
- Extensión debe ser `.jpg` o `.png`

### ❌ "El diseño se ve raro"
✅ **Solución**: 
- Presiona `Ctrl+Shift+R` para recargar
- Verifica que todos los archivos CSS estén en `styles/`

### ❌ "El texto es muy largo"
✅ **Solución**: 
- Reduce el texto o divide en párrafos
- El sitio es responsive, se ajustará

---

## 📞 ¿Necesitas Más Ayuda?

📖 Lee el archivo completo: **[INSTRUCTIONS.md](INSTRUCTIONS.md)**

---

**¡Listo! Ahora empieza a personalizar tu Momentum blog! 🎉**
