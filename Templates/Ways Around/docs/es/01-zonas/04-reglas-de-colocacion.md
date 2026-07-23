# Reglas de colocación

Las reglas de colocación determinan en qué parte de la zona se genera un objeto obligatorio. El objetivo es el punto de referencia de la regla: `MainObject` es la ciudad u objeto principal de la zona, `Crossroads` es su cruce interno de caminos y `Connection` es la salida indicada hacia otra zona.

| Objeto | Zona(s) | Objetivo | Rango (distancia minima/maxima al objetivo) | Peso |
|---|---|---|---|---:|
| Aserradero, Mina de minerales | Spawn-A/B | Ciudad inicial (`MainObject 0`) | 0.05-0.18 | 10 |
| Laboratorio de investigación | Center-A/B | Crossroads | 0.45-1.00 | 10 |
| Utopia de Dragones | Center | Crossroads | 0.45-1.00 | 10 |
| Estructura anómala | Center | Crossroads | 0.45-1.00 | 10 |
| Espejo de Spawn | Spawn-A/B | Ciudad inicial (`MainObject 0`) | 0.00-0.06 | 30 |

Otros elementos obligatorios, incluidos los pozos de maná, espejos de destino y extremos de portales, usan conexiones con nombre para que su ubicación corresponda a una salida concreta.
