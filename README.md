# Presentación a Presidencia · Mercadeo Digital y Omnicanalidad, Fajitex

Página web de una sola vista para presentar los resultados de la gestión del canal digital
y la ruta hacia la meta de $500.000.000 de venta mensual.

## Cómo se usa

Abra `index.html` en cualquier navegador. No necesita servidor ni instalación.
Para proyectar, use pantalla completa con la tecla F11 y recorra la página con la
navegación fija de la parte superior.

Requiere conexión a internet para cargar las fuentes tipográficas y la librería de gráficos.

## Cómo se completan los datos

Toda cifra que aún no está confirmada aparece resaltada en amarillo con la nota
"completar con dato real". Ninguna cifra pendiente fue estimada ni inventada.

Hay dos formas de llenarlas:

1. **Desde la página.** Botón "Completar datos" en la esquina inferior derecha.
   Los valores quedan guardados en el navegador donde se escriben y actualizan
   los textos, los medidores y los dos gráficos al instante.
2. **Desde el código.** Objeto `DATOS_BASE` al inicio del bloque `<script>` de
   `index.html`. Es la opción recomendada si la presentación se va a proyectar
   desde otro equipo, porque los valores viajan con el archivo.

Las palabras clave de la sección de SEO se cargan una por línea con el formato
`palabra clave, posición, volumen mensual`.

## Estructura de la página

1. Objetivo y metas mensuales de $250.000.000 y $500.000.000
2. Lo que es cierto y medible, solo con datos de Shopify
3. Diagnóstico heredado del canal
4. Auditoría de tracking, hallazgos y estado de cada corrección
5. La brecha de ROAS y el hallazgo de convergencia entre GA4 y Shopify
6. SEO y GEO, oportunidad identificada y plan de tres fases
7. El equipo que lo ejecuta y qué aporta cada rol
8. Plan escalonado hacia la meta final
9. Decisiones que se necesitan de Presidencia

## Detalles técnicos

Un solo archivo HTML con CSS y JavaScript propios, sin backend.
Gráficos con Chart.js 4.4.1 desde CDN. Tipografías Fraunces e Instrument Sans
desde Google Fonts. Animaciones respetan la preferencia de movimiento reducido
del sistema operativo y la página tiene hoja de estilos para impresión.
