# Guardias

## Guardias de encuentros generados

El contenido aleatorio protegido se coloca en estructuras de encuentro que pueden contener varias localizaciones u objetos recogibles tras un mismo ejército. El generador suma el `guardValue` de cada elemento colocado en el encuentro, aplica el multiplicador de guardia de la zona y después aplica la variación aleatoria y el crecimiento semanal configurados.

La siguiente tabla muestra el multiplicador de guardia, la variación aleatoria y el crecimiento semanal aplicados a los encuentros generados en cada zona.

| Zona | Multiplicador de guardia | Variación aleatoria | Crecimiento semanal |
|---|---:|---:|---:|
| Spawn-A / Spawn-B | 1.00 | 0.05 | 0.20 |
| Side-A / Side-B | 1.25 | 0.05 | 0.20 |
| Center-A / Center-B | 1.25 | 0.05 | 0.20 |
| Center | 1.25 | 0.05 | 0.20 |

Estos valores se aplican a las guardias generadas para el contenido de las zonas. Las guardias de conexiones y ciudades utilizan sus propios valores explícitos, mostrados a continuación.

## Conexiones terrestres

| Conexión | Valor de guardia | Crecimiento semanal |
|---|---:|---:|
| Spawn-A - Side-A | 14000 | 0.20 |
| Spawn-A - Center-A | 20000 | 0.20 |
| Side-A - Center | 40000 | 0.20 |
| Side-A - Center-B | 50000 | 0.20 |
| Spawn-B - Side-B | 14000 | 0.20 |
| Spawn-B - Center-B | 20000 | 0.20 |
| Side-B - Center | 40000 | 0.20 |
| Side-B - Center-A | 50000 | 0.20 |
| Center - Center-A | 35000 | 0.20 |
| Center - Center-B | 35000 | 0.20 |

La plantilla permite varias rutas de progresión. En un orden de ruptura típico, el acceso Side de 14000 es la apertura más ligera, después llega el acceso directo al tesoro de 20000, y las rutas hacia Center y las conexiones cruzadas exigen un ejército mayor. Los portales de retorno no tienen guardia.

## Guardias de ciudades

| Zona | Probabilidad | Fuerza | Crecimiento semanal |
|---|---:|---:|---:|
| Side-A / Side-B | 100% | 10000 | 0.10 |
| Center | 100% | 15000 | 0.10 |
