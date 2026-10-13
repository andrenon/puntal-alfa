# puntal · demo alfa

Demo público de **puntal**, un cliente web FEM para estructuras 1D (pórticos y
barras, 6 grados de libertad por nodo, análisis lineal elástico). Este
repositorio contiene **solo el build estático del demo**: el desarrollo vive en
un repositorio privado y cada versión estable se publica manualmente desde ahí.

## Probarlo

1. Entrá a <https://andrenon.github.io/puntal-alfa/>
2. Botón **Load demo**: pórtico de acero de 6.0 m de luz × 3.5 m de altura
   (sección IPE 240, empotramiento a la izquierda, apoyo biela a la derecha) con
   **resultados ya calculados embebidos en el archivo** — diagramas de esfuerzos
   (M3 activo por defecto), deformada y tablas, todo sin servidor.
3. Explorá el modelado: nodos, barras, apoyos, cargas, materiales, secciones y
   navegación de tablas.

El botón **Calculate** requiere el backend de cálculo (OpenSeesPy), que este demo
estático no incluye: al pulsarlo verás el error amable previsto.

## Qué es puntal

Modelado, cálculo y post-procesado de estructuras con elementos 1D. Motor
OpenSeesPy, borde IFC intacto (los resultados viajan embebidos como Psets) y una
arquitectura lista para migrar el motor de cálculo a WebAssembly dentro del
navegador, sin cambiar la interfaz.

## Aviso

Software experimental con fines de demostración. **No apto para diseño
profesional** ni para verificación de seguridad estructural.
