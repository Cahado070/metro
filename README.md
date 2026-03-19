# metro

Ejercicio de laboratorio de CSS

## Justificación

En el contexto del desarrollo de Software, la creación de interfaces no solo requiere estética,
sino robustez técnica y accesibilidad universal. Este curso utiliza el sistema de transporte
masivo de la ciudad de Medellín como un ”laboratorio vivo” para que el estudiante
resuelva problemas reales de maquetación, optimización y experiencia de usuario (UX),
aplicando metodologías modernas de arquitectura CSS.

## Competencias a desarrollar

- Técnica: Aprender a organizar el código CSS de forma ordenada para que el proyecto
  sea fácil de entender y crecer a futuro.
- Práctica(Resolutiva): Capacidad de construir interfaces reales que funcionen y se vean
  bien tanto en celulares como en computadores.
- Para todos(Inclusiva): Asegurar que el sitio web sea fácil de usar para cualquier ciudadano,
  incluyendo a personas con alguna discapacidad.
- De diagnóstico(Analítica): Aprender a encontrar fallos en la página y entender por
  qué puede cargar lento cuando el internet es deficiente.

## Contenido temático

### Unidad 1: Arquitectura de Maquetación y Diseño Adaptativo (35 Horas)

**Objetivo:** Construir el esqueleto de la ”Estación Digital” de forma escalable.

1. Metodologías de Organización (ITCSS): Capas de configuración, herramientas, genéricos
   y componentes.
2. Nomenclatura Profesional (BEM): Definición de Bloque, Elemento y Modificador aplicado
   al componente civica-card.
3. Flexbox Avanzado: Ejes y alineación de la barra de navegación (Header Metro). Distribución
   de estados de servicio (Línea A, B, T) mediante flex-grow y gap.
4. CSS Grid System: Maquetación del ”Mapa de Red” mediante áreas y tracks. Grid implícito
   vs. explícito aplicado a la sección ”Estaciones Favoritas”.
5. Estrategia Mobile-First: Uso de Media Queries lógicas y unidades relativas (rem, em,
   vh, vw).

### Unidad 2: Integración Multimedia y Optimización SEO (25 Horas)

Objetivo: Gestionar activos visuales de alto impacto con bajo costo de transferencia de datos.

1. Gráficos Vectoriales (SVG): Implementación de iconos de estaciones y logotipos con
   manipulación de color vía CSS.
2. Imágenes Responsivas: Uso de srcset y <picture> para cargar diferentes versiones del
   Mapa de Red según el dispositivo.
3. Formatos de Nueva Generación: Implementación de WebP y AVIF para reducir el peso
   de las fotos de estaciones.
4. SEO Semántico: Jerarquía de encabezados (h1-h6) y meta-etiquetas de geolocalización
   para búsqueda de rutas.
5. Open Graph: Configuración de tarjetas compartibles para el estado del servicio en
   tiempo real.

### Unidad 4: Proyecto Integrador: Laboratorio ”Estación Digital” (30 Horas)

Objetivo: Desarrollo de una aplicación web funcional de una estación específica del sistema.

1. Fase 1 (Investigación): Análisis de necesidades de la estación elegida (ej. Estación
   Universidad - Perfil Estudiantil).
2. Fase 2 (Prototipado): Diseño en Figma siguiendo la guía de estilos establecida.
3. Fase 3 (Codificación): Desarrollo bajo arquitectura ITCSS + BEM.
4. Fase 4 (Despliegue y Demo): Publicación en Netlify/Vercel y sustentación técnica.

## Metodología de Aprendizaje

El curso se basa en el modelo PBL (Project Based Learning). Cada bloque de 20 minutos
de teoría es seguido por 40 minutos de ”Live Coding” donde el docente y los alumnos
construyen juntos el portal del Metro.

## Evaluación y evidencias

Evidencia Descripción Peso

---

Taller BEM Maquetación de la Tarjeta Cívica con 3 modificadores
de perfil.
20%
Grid Challenge Creación del panel de estaciones favoritas con diseño
responsivo.
20%
Audit Report Informe de corrección de accesibilidad y SEO de una
interfaz dada.
20%
Proyecto Final Landing page completa de una estación (Código +
Despliegue).
40%
