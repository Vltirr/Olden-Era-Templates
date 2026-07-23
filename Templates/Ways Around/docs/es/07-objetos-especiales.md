# Objetos especiales

## Espejos del Mundo

Cada espejo de Spawn esta junto a la ciudad inicial y revela un radio de 10 alrededor de dos espejos remotos.

| Espejo inicial | Espejos revelados |
|---|---|
| Spawn-A | Side-A y Center-A |
| Spawn-B | Side-B y Center-B |

Los espejos de Side se colocan junto a la conexión Spawn-Side. Los de Center-A/B se colocan junto a su conexión Spawn-Center. Reutilizan el aspecto de Flattering Mirror, pero usan IDs y lógica propios en el paquete de assets.

## Portales de retorno

| Desde | Hasta | Colocación del origen | Colocación en Spawn |
|---|---|---|---|
| Side-A | Spawn-A | Cerca de la ciudad | Cerca de Spawn-A - Center-A |
| Center-A | Spawn-A | Cerca del crossroads | Cerca de Spawn-A - Side-A |
| Side-B | Spawn-B | Cerca de la ciudad | Cerca de Spawn-B - Center-B |
| Center-B | Spawn-B | Cerca del crossroads | Cerca de Spawn-B - Side-B |

Todos son unidireccionales, usan rango `0.00-0.08`, peso `20` y tienen carretera a ambos extremos.

## Pozos de maná

| Zona | Pozo de maná obligatorio situado cerca de |
|---|---|
| Spawn-A | Spawn-A - Side-A |
| Side-A | Side-A - Center-B |
| Center-A | Spawn-A - Center-A |
| Spawn-B | Spawn-B - Side-B |
| Side-B | Side-B - Center-A |
| Center-B | Spawn-B - Center-B |
| Center | Side-A - Center; Side-B - Center; Center - Center-A; Center - Center-B |

Cada zona fuera de Center tiene un pozo de maná obligatorio junto a la salida indicada. Center tiene cuatro, uno junto a cada entrada directa. Center-A/B también contienen un Chapitel celestial; ver [contenido obligatorio](01-zonas/07-contenido-obligatorio.md).
