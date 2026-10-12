# Reglas del Proyecto: FONTANERÍA REFORMAS

Estas reglas guían todo el desarrollo, diseño, arquitectura y mantenimiento de la presencia digital para el negocio **FONTANERÍA REFORMAS**.

---

## 1. Identidad del Negocio y Datos Clave

- **Nombre Comercial**: FONTANERÍA REFORMAS (F&R)
- **Actividades Principales**:
  - Fontanería profesional y desatascos / instalaciones.
  - Reformas integrales (viviendas, locales, baños, cocinas).
  - Venta de herramientas y materiales de construcción.
  - Venta e instalación de aire acondicionado y agua caliente (termos, calderas, aerotermia).
  - Pintura profesional y acabados.
  - Electricidad e iluminación.
  - Albañilería en general.
- **Experiencia**: Más de 20 años de experiencia en el sector.
- **Ubicación Física**:
  - Dirección: Calle Carlos Martín Álvarez, 64 Bis
  - Código Postal: 28053
  - Localidad / Distrito: Madrid / Vallecas
- **Canales de Contacto Directo**:
  - Teléfono fijo tienda/oficina: `919 126 130`
  - Teléfonos móviles / WhatsApp: `685 659 064` / `643 10 05 29`
  - Correo electrónico: `fontaneria.reformas1@gmail.com`
- **Identidad Visual del Logotipo**:
  - Colores base: Azul corporativo (#1e3a8a / #1d4ed8 / #0f172a), Blanco (#ffffff), detalles en Ámbar/Naranja de acción (#f59e0b / #ea580c) y Verde WhatsApp (#25d366).
  - Isotipo / Emblema: Emblema circular donde figura "FONTANERÍA" y "CONSTRUCCIÓN", junto con el icono de casa, llave inglesa y muro de ladrillos representativo de "F&R Reformas y Albañilería".

---

## 2. Principios de Diseño y Experiencia de Usuario (UX/UI)

1. **Mobile-First & Ultra Responsive**:
   - Más del 75% de los clientes que buscan fontaneros o reformas de urgencia lo hacen desde su smartphone.
   - La cabecera, botones de llamada y WhatsApp deben ser accesibles en todo momento con una barra de acción inferior o botones flotantes visibles en móviles.
2. **Alta Conversión (CRO)**:
   - Llamadas a la acción (CTAs) visibles y claras: "Llamar ahora", "Pedir presupuesto por WhatsApp", "Solicitar visita sin compromiso".
   - Botón directo de WhatsApp con mensaje preconfigurado (ej: *"Hola, me gustaría solicitar presupuesto para..."*).
   - Teléfono fijo y móvil clicables directamente con protocolo `tel:`.
3. **Credibilidad y Confianza**:
   - Destacar los **20 años de experiencia**, garantía por escrito, presupuestos transparentes sin compromiso y atención rápida en Madrid y alrededores.
   - Sección de opiniones de clientes reales, proceso de trabajo en 4 pasos sencillos y sección de preguntas frecuentes (FAQ).
4. **Accesibilidad y Rendimiento**:
   - HTML semántico estricto (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
   - Contraste de colores adecuado (WCAG AA).
   - Sin dependencias pesadas innecesarias; carga instantánea.

---

## 3. SEO Local y Metadatos

- **Estructura Semántica para Madrid / Vallecas**:
  - Etiquetas Title y Meta Description optimizadas para palabras clave locales: "Fontanería en Vallecas", "Reformas Integrales Madrid", "Instalación Aire Acondicionado Vallecas", "Materiales de Construcción Madrid".
- **Datos Estructurados (Schema.org)**:
  - Implementar bloque JSON-LD tipo `HomeAndConstructionBusiness` / `Plumber` / `GeneralContractor` con dirección completa, geo-coordenadas aproximadas, horarios y teléfonos.
- **Open Graph y Twitter Cards**:
  - Configurados para previsualización atractiva al compartir enlaces por WhatsApp, Telegram o redes sociales.

---

## 4. Estándares Técnicos del Código

- **Frontend**: HTML5 moderno, CSS3 con variables personalizadas (CSS Custom Properties), animaciones fluidas con `transition` y `keyframes`, Flexbox y CSS Grid.
- **Interactividad**: JavaScript nativo (ES6+) limpio, modular, sin dependencias externas pesadas para garantizar velocidad máxima.
- **Recursos**: Iconografía SVG escalable y ligera, imágenes optimizadas con atributos `loading="lazy"` y etiquetas `alt` descriptivas.
