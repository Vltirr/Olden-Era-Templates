# Presupuestos y recompensas

| Zona | Protegido | Sin proteger | Recursos | Total |
|---|---:|---:|---:|---:|
| Center | 350000 | 25000 | 75000 | 450000 |
| Center-A / Center-B | 275000 | 25000 | 50000 | 350000 |
| Side-A / Side-B | 225000 | 20000 | 60000 | 305000 |
| Spawn-A / Spawn-B | 175000 | 15000 | 50000 | 240000 |

`Protegido` es el presupuesto de encuentros con guardianes externos en el mapa. `Sin proteger` es el presupuesto de objetos situados sin guardián externo. `Recursos` se reserva para recursos sueltos. `Total` es la suma de los tres.

La distribución protegida de Center es `[0, 1, 2, 6, 5, 5]`, concentrando valor en los tramos superiores. Center-A/B usan `[1, 3, 4, 6, 3, 2]`, con tesoros fuertes pero menos valor máximo.

El grupo protegido de artefactos aleatorios tiene peso `60000` tanto en Center como en Center-A/B. Center puede seleccionar artefactos raros, épicos o legendarios con pesos relativos `25/50/25`; Center-A/B puede seleccionar artefactos raros o épicos con pesos `25/50`. Los artefactos comunes tienen peso `0` en ambos pools y los legendarios siguen prohibidos en Center-A/B.

- Spawn se centra en minas, bancos tempranos y recursos iniciales.
- Side añade ciudad propia, economía fuerte y acceso a bancos T3.
- Center-A/B ofrecen moradas avanzadas de un solo uso, laboratorio y artefactos épicos.
- Center añade ciudad neutral, Utopía de Dragones, Estructura anómala, artefactos legendarios y épicos, y el mayor presupuesto total.
