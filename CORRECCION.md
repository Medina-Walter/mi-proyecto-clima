# Corrección de Mala Práctica

## Mala Práctica Identificada
**Falta de documentación en el código HTML.**  
El archivo index.html no contenía comentarios que explicaran la estructura, propósito o funcionalidad de las secciones del código.

## ¿Por Qué es una Mala Práctica?
Sin comentarios, es difícil entender la intención de cada sección, lo que complica futuras modificaciones.
Los comentarios son esenciales para que nuevos desarrolladores comprendan rápidamente el código.
- **Falta de claridad:** Interpretar el código sin documentación consume tiempo y puede llevar a errores.

## Solución Implementada
Se agregaron comentarios descriptivos en index.html para documentar:
- La estructura general del documento.
- Las secciones principales (header, main, dashboard, mapa, footer).
- Componentes clave como estados de carga, tarjeta de clima y controles del mapa.

Los comentarios son claros, concisos y explican el propósito de cada bloque de código.

## Beneficios de la Solución
- **Mejor mantenibilidad:** Los desarrolladores pueden entender rápidamente el propósito de cada sección.
- **Escalabilidad:** Un código bien documentado es más fácil de extender en el futuro.



### Mala Práctica: Enlace al CSS no echo

### ¿Por Qué es una Mala Práctica?
- **Experiencia del usuario:** Si el CSS no se carga, la página se renderizará sin estilos, resultando en un diseño roto o ilegible.
- **Accesibilidad:** Un diseño sin estilos puede dificultar la navegación para usuarios, especialmente aquellos que dependen de un formato visual claro.

### Solución Implementada
- Se agregó el atributo type="text/css al enlace link para seguir las mejores prácticas de HTML5.