# Global Logistics API — Métricas de plataforma y caso de valor

Presentación interactiva que defiende al Platform Engineering Team de Global Logistics API ante un recorte del 15 %. Traduce el Golden Path a dólares: $45.000 de espera evitada por aprovisionamiento y $450.000 en una ronda de 10 equipos, además del Cost of Delay. Presenta un tablero para el CTO con Lead Time for Changes y su señal líder, dos métricas SPACE agregadas por equipo y la adopción voluntaria como KPI. Explica cómo la experiencia de desarrollo desincentiva el Shadow IT sin medidas punitivas. Elaborada para Arquitectura de Plataformas (ARTI-4219), Universidad de los Andes.

[Ver la presentación interactiva](https://raparram.github.io/Global-Logistics-API/)

## Archivo de entrega y revisión local

`index.html` contiene el documento completo, con los cinco autores, estilos, scripts, la animación de portada y el diagrama SVG integrados. Es el archivo único de entrega. Las fuentes web tienen alternativas locales, por lo que el contenido también se puede consultar sin conexión. `Global-Logistics-API.html` es únicamente un acceso mediante iframe y necesita `index.html` a su lado.

Para revisarlo, abre `index.html` en un navegador o ejecuta `python3 -m http.server 8765` desde esta carpeta y visita <http://localhost:8765/>.

La vista inicial muestra una síntesis por bloque. Los apartados desplegables conservan los cálculos, las fichas de cada métrica y el análisis de DevEx. En «Contenido», el botón «Mostrar análisis completo» abre todos los apartados. Los enlaces directos a una sección detallada abren su apartado automáticamente. Al imprimir se abren todos los apartados.

## Correspondencia con la rúbrica

| Criterio | Evidencia en el documento |
| --- | --- |
| Modelado financiero y justificación de valor (ROI y Cost of Delay) | Bloque I: cálculo unitario ($50.000 − $5.000 = $45.000), proyección a 10 equipos ($450.000), sensibilidad frente al costo estimado del equipo, punto de equilibrio, escenarios A (aceleración de ingresos) y B (eficiencia) de S14, umbral de Cost of Delay y enunciado de dos líneas para la junta. |
| Ecosistema de métricas y tablero ejecutivo (DORA, SPACE y KPIs) | Bloque II: tablero con M1 Lead Time for Changes (lagging) y M2 tiempo por etapa (leading), M3 y M4 de SPACE con límites de uso, M5 adopción voluntaria, fichas con fórmula, fuente, meta y decisión, y mapa de señales R1–R3. |
| Estrategia DevEx y prevención orgánica de Shadow IT | Bloque III: bucles de retroalimentación de 20 a 2 días, carga cognitiva extrínseca, medidas objetivas y subjetivas por dimensión DevEx, cadena fricción → atajo → elección, cuatro mecanismos no punitivos y alternativas descartadas. |
| Estructura, rigor conceptual y comunicación ejecutiva | Síntesis por bloque con detalle desplegable, cifras que cierran, hechos y supuestos separados, respuesta a la junta, hoja de ruta, riesgos, supuestos y referencias. |

El diagrama editable está en `diagramas/tablero-global-logistics-api.drawio`. Sus identificadores M1–M5 y R1–R3 corresponden al SVG incorporado en `index.html` y a la tabla 2.4; cualquier cambio debe conservar esa correspondencia.
