# Sistema de Diseño Suprabond · ERPA

Lenguaje visual de la marca **ERPA / Suprabond**. Fundamentos, tono y componentes para construir experiencias consistentes en tienda, web y producto.

**Versión:** 1.0 · 2026

---

## 📁 Contenido

| Archivo | Descripción |
|---|---|
| `Sistema de Diseño Suprabond.dc.html` | Guía completa — modo claro |
| `Sistema de Diseño Suprabond Dark.dc.html` | Guía completa — modo oscuro |
| `Suprabond Tokens One-Pager.dc.html` | Referencia portátil (A4) imprimible a PDF |
| `support.js` | Runtime necesario para abrir los `.dc.html` |

Cada `.dc.html` se abre directamente en el navegador (doble clic).

---

## 🎨 Color

### Marca
| Token | Hex | Uso |
|---|---|---|
| Amarillo Suprabond | `#FFD400` | Primario · CTAs, marca, destacados |
| Celeste | `#29ABE2` | Acento · enlaces, info, secundarios |
| Negro | `#111315` | Texto principal, fondos sólidos |
| Blanco | `#FFFFFF` | Superficies, tarjetas, fondos |

### Neutros
`#111315` · `#2D3138` · `#5A626B` · `#8A9099` · `#C9CDD2` · `#ECEDEF` · `#F4F5F6`

### Semánticos
| Estado | Hex |
|---|---|
| Éxito | `#1B8A5A` |
| Aviso | `#B25E09` |
| Error | `#E5484D` |

### Base modo oscuro
Fondo `#0C0E10` · Superficie `#16191D`

---

## ✍️ Tipografía

- **Títulos:** Poppins Bold (weights 600 / 700 / 800, tracking `-0.02em`)
- **Texto:** Google Sans (weights 400 / 500 / 700) — *fallback:* DM Sans

> Google Sans no es de licencia libre. Los archivos usan **DM Sans** como sustituto fiel para el render; reemplazar por la fuente real donde esté disponible.

### Escala
| Nivel | Fuente | Tamaño · line-height |
|---|---|---|
| Display / H1 | Poppins 800 | 48px · 1.0 |
| H2 Sección | Poppins 700 | 32px · 1.1 |
| H3 Subtítulo | Poppins 600 | 22px · 1.2 |
| Body | Google Sans 400 | 15px · 1.7 |
| Small / Label | Google Sans 500 | 13px · 1.5 |

---

## 🧩 Componentes

- **Botones** — primario (amarillo), oscuro, outline (celeste), texto, deshabilitado · tamaños sm/md/lg
- **Formularios** — estados default, focus, error, deshabilitado
- **Badges** — marca, oferta, destacado, stock
- **Tarjeta de producto**
- **Header de tienda**

### Tokens de sistema
```
radius:      8 · 10–14 · 18 (cards)
card:        #fff + shadow 0 1px 3px rgba(0,0,0,.06)
focus ring:  0 0 0 3px rgba(41,171,226,.15)
espaciado:   4 · 8 · 14 · 18 · 22 · 30
```

---

## 🚀 Uso

Abrí cualquier `.dc.html` en el navegador. Para una referencia rápida y portátil, imprimí `Suprabond Tokens One-Pager.dc.html` a PDF (Cmd/Ctrl + P).
