# Sistema de Diseño — LLC Certificaciones

## Marca y principios visuales

**Propósito**: Transmitir autoridad técnica, confianza normativa y profesionalismo corporativo en el sector de certificación eléctrica colombiana.

**Principios**:
- Limpieza y espacio en blanco generoso
- Jerarquía tipográfica clara
- Colores institucionales sobrios con un acento energético
- Componentes bien definidos con bordes sutiles

---

## Paleta de colores

| Token           | Hex       | Uso principal                              |
|----------------|-----------|---------------------------------------------|
| `primary-900`  | `#0B1F4B` | Header, footer, fondos oscuros              |
| `primary-800`  | `#0D2860` | Variante oscura de fondo                    |
| `primary-700`  | `#1040A0` | Botones primarios, títulos sobre fondo claro|
| `primary-600`  | `#1A56C8` | Hover de botón primario                     |
| `primary-500`  | `#1E6FE8` | Links activos, íconos                       |
| `primary-100`  | `#DBEAFE` | Fondos de badge/chip azul claro             |
| `accent-500`   | `#F59E0B` | CTAs secundarios, highlights, badges        |
| `accent-400`   | `#FBBF24` | Hover states del accent                     |
| `accent-100`   | `#FEF3C7` | Fondos sutiles con acento                   |
| `surface`      | `#F8FAFC` | Fondo de secciones alternas                 |
| `white`        | `#FFFFFF` | Fondo principal                             |
| `text-primary` | `#0F172A` | Títulos y texto principal                   |
| `text-body`    | `#334155` | Párrafos y cuerpo de texto                  |
| `text-muted`   | `#64748B` | Texto secundario, captions                  |
| `border`       | `#E2E8F0` | Bordes de tarjetas, separadores             |
| `border-dark`  | `#CBD5E1` | Bordes con mayor contraste                  |

---

## Tipografía

**Fuente**: Inter (Google Fonts) — 400, 500, 600, 700, 800

| Nivel    | Tamaño      | Peso | Line-height | Uso                    |
|---------|-------------|------|-------------|------------------------|
| Display | 3.75–4.5rem | 800  | 1.1         | Hero headline          |
| H1      | 3rem        | 800  | 1.15        | Títulos de página      |
| H2      | 2–2.25rem   | 700  | 1.2         | Títulos de sección     |
| H3      | 1.25rem     | 600  | 1.3         | Títulos de tarjeta     |
| Body    | 1rem        | 400  | 1.7         | Texto de párrafo       |
| Small   | 0.875rem    | 500  | 1.5         | Labels, captions       |
| Micro   | 0.75rem     | 600  | 1.4         | Badges, chips          |

---

## Espaciado y layout

- **Container max-width**: 1280px (`max-w-7xl`) centrado con `px-6` (móvil) / `px-8` (desktop)
- **Section padding**: `py-20` a `py-28`
- **Card padding interno**: `p-8`
- **Gap entre elementos de grid**: `gap-6` a `gap-8`
- **Border-radius**:
  - Tarjetas: `rounded-2xl`
  - Botones: `rounded-lg` a `rounded-xl`
  - Badges/pills: `rounded-full`
  - Íconos de fondo: `rounded-xl`

---

## Componentes

### Botones

**Primario (azul)**
- Fondo: `#1040A0` → hover `#1A56C8`
- Texto: blanco, 500, 0.9375rem
- Padding: `px-7 py-3.5`
- Sombra: `shadow-md` → hover `shadow-lg`
- Transición: `transition-all duration-200`

**Secundario (outline)**
- Borde: `#1040A0` 1.5px
- Texto: `#1040A0`, 500
- Fondo: transparente → hover fondo azul claro `#DBEAFE`

**Acento (amarillo)**
- Fondo: `#F59E0B` → hover `#FBBF24`
- Texto: `#0B1F4B`, 700
- Mismos paddings y radio que primario

### Tarjetas de servicio
- Fondo: blanco
- Borde: `1px solid #E2E8F0`
- Radio: `rounded-2xl`
- Sombra: `shadow-sm` → hover `shadow-lg`
- Hover: borde cambia a `#1040A0` + ligero translate-y (-2px)
- Transición: `transition-all duration-200`

### Íconos de sección
- Contenedor: `rounded-xl` con fondo `#DBEAFE`
- Ícono SVG: color `#1040A0`
- Tamaño contenedor: 56x56px (w-14 h-14)

### Badges / chips
- Padding: `px-3 py-1`
- Radio: `rounded-full`
- Texto: 0.75rem / 600
- Variante azul: bg `#DBEAFE`, text `#1040A0`
- Variante amarilla: bg `#FEF3C7`, text `#92400E`

---

## Efectos visuales

- **Sombras**: escala `shadow-sm` → `shadow-md` → `shadow-lg` según nivel de elevación
- **Transiciones**: `transition-all duration-200 ease-in-out`
- **Hover en tarjetas**: `translateY(-2px)` + `shadow-lg` + borde azul
- **Glassmorphism nav**: `backdrop-blur-md bg-white/95` al hacer scroll
- **Hero background**: gradiente `from-[#0B1F4B] via-[#0D2860] to-[#1040A0]` con patrón geométrico SVG overlay
- **Separadores de sección**: border-bottom sutil `#E2E8F0` o transición de color de fondo

---

## Responsive

| Breakpoint | Prefijo TW | Columnas de grid  |
|------------|------------|-------------------|
| < 640px    | (base)     | 1 columna         |
| 640–768px  | `sm:`      | 1–2 columnas      |
| 768–1024px | `md:`      | 2 columnas        |
| 1024px+    | `lg:`      | 3–4 columnas      |
| 1280px+    | `xl:`      | max-width fijo    |

**Mobile-first**: Todos los componentes diseñados mobile-first y expandidos hacia desktop.

---

## Voz visual de la marca

- **No usar**: diseños recargados, gradientes de neón, animaciones excesivas, tipografías decorativas
- **Sí usar**: espacios generosos, líneas limpias, íconos lineales simples, fotografía técnica/industrial
- **Sensación**: corporativo premium, técnico confiable, institucional moderno
