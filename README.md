# Cimas Vivas

Juego web educativo sobre los ecosistemas de México. La persona jugadora debe equilibrar una torre de árboles mientras descubre especies, datos de conservación y recomendaciones de cuidado.

Autora: **Aixa Margarita Gonzales Amador**  
Correo: **ga202508926@alm.buap.mx**

## Enlace de la aplicación

https://marga222.github.io/cimas-vivas-mexico/

## Tecnologías

- HTML5 para la estructura semántica de las secciones de juego, aprendizaje, ranking y referencias.
- CSS3 con una plantilla de escritorio y una adaptación responsiva para móvil mediante `@media`.
- JavaScript para controles, guardado del ranking con `localStorage`, cambio de especies y mecánica del juego.

## Mejoras del prototipo

1. Se añadió una sección de referencias con enlaces a CONABIO, SEMARNAT y FAO.
2. El diseño se adapta a pantalla de computadora y teléfono móvil.
3. La aparición del viento usa valores aleatorios con `Math.random()` para que cada partida sea distinta.
4. Se mejoró el equilibrio con un modelo de movimiento angular inspirado en *Nature of Code*: fuerza de viento, fuerza restauradora y amortiguamiento generan un comportamiento gradual de la torre.
5. El ranking se conserva localmente en el navegador para promover la competencia entre jugadores del mismo dispositivo.

## Ejecución

Abre `index.html` en un navegador moderno o visita el enlace publicado. Para desarrollar localmente se recomienda usar la extensión Live Server de Visual Studio Code.

## Fuentes

- [CONABIO — Ecosistemas de México](https://www.biodiversidad.gob.mx/ecosistemas)
- [SEMARNAT](https://www.gob.mx/semarnat)
- [FAO — Bosques y recursos forestales](https://www.fao.org/forestry/es/)
- [The Nature of Code](https://natureofcode.com/)
