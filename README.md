# 🤖 AI Academy - Cursos de IA y Apps para Ganar Dinero

Landing page profesional y moderna para promocionar cursos en línea EN VIVO por Google Meet.

## 🚀 Características

### Diseño
- **Estilo futurista/tecnológico** con colores azul eléctrico, negro, morado oscuro y detalles en verde neón
- **Modo oscuro** por defecto para estética tech
- **Diseño 100% responsive** (móvil, tablet y escritorio)
- **Animaciones suaves** al hacer scroll (scroll-triggered animations)
- **Partículas animadas** y gradientes dinámicos en el hero
- **Tipografía moderna** y limpia

### Secciones
1. **Header/Navegación** - Sticky con logo, menú, iconos de redes sociales y CTA
2. **Barra de Urgencia** - Texto de oferta con código de descuento animado
3. **Hero/Banner** - Título animado, CTAs, indicadores de confianza y contador regresivo
4. **¿Por qué elegirnos?** - 6 tarjetas con iconos y efectos hover
5. **Cursos de IA** - ChatGPT, Google Gemini, Qwen y más con badges "EN VIVO"
6. **Apps para Ganar Dinero** - FreeCash, Gamony, Timebucks y más
7. **¿Cómo Funciona?** - Línea de tiempo de 5 pasos
8. **Planes y Precios** - 3 planes (Básico, Intermedio, Premium)
9. **Testimonios** - Carrusel de reseñas de estudiantes
10. **FAQ** - Acordeón con preguntas frecuentes
11. **Formulario de Contacto** - Con checkboxes de cursos y envío por WhatsApp
12. **Footer** - Links, redes sociales e información de contacto
13. **Botón Flotante de WhatsApp** - Con animación de pulso y tooltip
14. **Pop-up de Salida** - Oferta especial al intentar salir de la página

### Funcionalidades
- ✅ Menú móvil hamburguesa
- ✅ Navegación suave (smooth scroll)
- ✅ Contador regresivo para próxima clase
- ✅ Formulario de inscripción que envía datos por WhatsApp
- ✅ Pop-up de salida con oferta especial
- ✅ Todos los enlaces de redes sociales abren en nueva pestaña
- ✅ SEO optimizado con meta tags
- ✅ Favicon personalizado

### Redes Sociales Integradas
- 📱 TikTok: [@ezequielmedina630](https://www.tiktok.com/@ezequielmedina630)
- 📸 Instagram: [@ezequielbenjamin1202](https://www.instagram.com/ezequielbenjamin1202)
- 💬 WhatsApp: [+58 412 912 6548](https://wa.me/584129126548)

## 🛠️ Tecnologías

- **React 19** - Biblioteca de UI
- **TypeScript** - Tipado estático
- **Vite 7** - Build tool
- **Tailwind CSS 4** - Framework de estilos utilitarios
- CSS personalizado con animaciones (@keyframes)

## 📦 Instalación

```bash
npm install
npm run dev
```

## 🏗️ Build

```bash
npm run build
```

## 📁 Estructura de Archivos

```
src/
├── App.tsx                    # Componente principal + Exit Popup
├── main.tsx                   # Entry point
├── index.css                  # Estilos globales, animaciones y tema
├── hooks/
│   └── useScrollAnimation.ts  # Hook para animaciones al scroll
├── components/
│   ├── Header.tsx             # Navegación sticky con redes sociales
│   ├── Hero.tsx               # Banner principal con partículas
│   ├── WhyUs.tsx              # Sección "¿Por qué elegirnos?"
│   ├── AICourses.tsx          # Cursos de Inteligencia Artificial
│   ├── MoneyCourses.tsx       # Apps para ganar dinero
│   ├── HowItWorks.tsx         # Pasos de cómo funciona
│   ├── Pricing.tsx            # Planes y precios
│   ├── Testimonials.tsx       # Carrusel de testimonios
│   ├── FAQ.tsx                # Preguntas frecuentes (acordeón)
│   ├── Contact.tsx            # Formulario de inscripción
│   ├── Footer.tsx             # Pie de página
│   └── WhatsAppButton.tsx     # Botón flotante de WhatsApp
└── utils/
    └── cn.ts                  # Utilidad para clases CSS
```

## 📝 Notas

- Los precios mostrados son placeholder ($15, $35, $59 USD). Actualizar según necesidad.
- El formulario de contacto envía los datos directamente a WhatsApp.
- El contador regresivo se actualiza automáticamente cada 3 días.
- Las animaciones se activan al hacer scroll (Intersection Observer).

---

© 2025 AI Academy — Todos los derechos reservados
