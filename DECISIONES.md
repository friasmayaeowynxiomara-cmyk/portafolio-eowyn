# DECISIONES — Portafolio de Eowyn Xiomara Frías Maya

Aquí explico POR QUÉ tomé cada decisión, para entenderla si vuelvo a este código en seis meses.

## 1. Estructura de secciones
Inicio, Sobre mí, Proyectos, Habilidades, Formación y Contacto. Es el orden que pide el capítulo 1.12 y además cuenta una historia: quién soy, qué hago, qué sé y cómo contactarme.

## 2. Identidad visual
- **Idea central:** mi página une química y computación, así que la sección de inicio lleva mi foto dentro de un marco con un brillo violeta, como el color del xenón en un tubo de descarga (el símbolo **Xe** de Xiomara).
- **Paleta (5 colores):**
  - Primario violeta `#5b35c9` (claro) / `#a68bff` (oscuro): el xenón brilla violeta-azulado en un tubo de descarga.
  - Acento turquesa `#0b7f94` (claro) / `#4fd1e6` (oscuro): contrasta bien con el violeta.
  - Fondo `#eef3f7` / `#0e1420`, superficie `#ffffff` / `#172033` y texto `#14212c` / `#e8edf4`.
- **Contraste:** pendiente de verificar cada par en WebAIM Contrast Checker (mínimo 4.5:1). Anotar resultados aquí:
  - [ ] Texto sobre fondo (claro): ____
  - [ ] Texto sobre fondo (oscuro): ____
  - [ ] Botón principal: ____

## 3. Tipografía
- **Bricolage Grotesque** para títulos: tiene personalidad y se ve moderna.
- **IBM Plex Sans** para el texto: es muy legible en pantallas pequeñas.
- Cada fuente tiene alternativas del sistema por si Google Fonts no carga.

## 4. Layout
- Mobile-first: se diseña primero para celular y se amplía a partir de 48rem.
- Proyectos y habilidades en 3 columnas en escritorio, 1 en celular.
- Etiquetas semánticas (header, nav, main, section, article, aside, footer) en lugar de divs genéricos.

## 5. Interactividad (4 funciones mínimas)
1. Menú hamburguesa en móvil (con aria-expanded y cierre con Esc).
2. Formulario con validación y mensajes de error claros.
3. Scroll suave en los enlaces internos (se desactiva si el usuario prefiere menos movimiento).
4. Modo oscuro con botón; respeta la preferencia del sistema y recuerda la elección.

## 6. Accesibilidad
Enlace "Saltar al contenido", foco visible, etiquetas en todos los campos, navegación completa con teclado, `lang="es"` y soporte de `prefers-reduced-motion`.

## 7. Qué cambiaría después
- Reemplazar los proyectos de ejemplo por proyectos reales con enlace a GitHub.
- Agregar una foto con texto alternativo descriptivo.
- Separar CSS y JS en archivos como pide la estructura recomendada del capítulo.

## 8. Retroalimentación recibida
| Persona | Qué comentó | Qué cambié |
|---|---|---|
| 1. ____ | ____ | ____ |
| 2. ____ | ____ | ____ |
