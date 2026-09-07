# Presentación a Presidencia · Mercadeo Digital y Omnicanalidad, Fajitex

Página web de una sola vista con el diagnóstico completo del canal digital
y el plan hacia la meta de $500.000.000 de venta mensual.

## Cómo se usa

Abra `index.html` en cualquier navegador. No necesita servidor ni instalación.
Para proyectar, use pantalla completa con la tecla F11 y recorra la página con la
navegación fija de la parte superior.

Requiere conexión a internet para cargar las fuentes tipográficas y la librería de gráficos.

## Logo

Coloque el archivo del logo en `assets/logo-fajitex.png`. Mientras no exista,
la barra de navegación muestra automáticamente la marca escrita "fajitex" como respaldo.

## Transparencia de datos

Cada cifra destacada lleva debajo, en texto pequeño, la fuente exacta de donde se tomó,
y cuando resulta de un cruce entre plataformas, el método de verificación.
Algunas cifras tienen además un ícono de información que despliega el método completo con un clic.

Las cifras que aún no están confirmadas aparecen resaltadas en amarillo con la nota
"completar con dato real". Ninguna fue estimada ni aproximada. Hoy quedan pendientes:

- El hito intermedio del plan escalonado
- Los montos del checklist de cierre

## Las dieciséis secciones

1. Objetivo, la meta escalonada
2. Por qué llegamos hasta aquí, el patrón de fondo
3. Shopify, lo que es cierto y medible
4. Agosto, el resultado oficial de Ventas B2C contra presupuesto
5. La migración de canal, por línea de producto
6. Diagnóstico heredado
7. La auditoría de tracking, hallazgos y estado
8. La brecha de ROAS, único quiebre de tono visual de la página
9. Contraste contra el informe interno de junio de 2026
10. Comparativo 2025 contra 2026
11. El patrón que se repite, cuatro agencias
12. SEO, la oportunidad ya identificada
13. Lo que dejamos de ganar, y lo que vamos a ganar
14. El equipo que lo ejecuta
15. Plan escalonado
16. Cierre, lo que se necesita de Presidencia

## Detalles técnicos

Un solo archivo HTML con CSS y JavaScript propios, sin backend.
Cinco gráficos con Chart.js 4.4.1 desde CDN, incluida una cascada simulada con barras flotantes.
Los datos de los gráficos están en objetos con nombre al inicio del bloque `<script>`,
al lado de la fuente correspondiente en el texto de la página.
Tipografías Fraunces e Instrument Sans desde Google Fonts.
Las animaciones respetan la preferencia de movimiento reducido del sistema operativo
y la página tiene hoja de estilos para impresión.
