# Objetos especiales

## Espejos del Mundo

Cada espejo de Spawn esta junto a la ciudad inicial y revela un radio de 10 alrededor de dos espejos remotos.

| Espejo inicial | Espejos revelados |
|---|---|
| Spawn-A | Side-A y Center-A |
| Spawn-B | Side-B y Center-B |

Los espejos de Side se colocan junto a la conexion Spawn-Side. Los de Center-A/B se colocan junto a su conexion Spawn-Center. Reutilizan el aspecto de Flattering Mirror, pero usan IDs y logica propios en el paquete de assets.

## Portales de retorno

| Desde | Hasta | Colocacion del origen | Colocacion en Spawn |
|---|---|---|---|
| Side-A | Spawn-A | Cerca de la ciudad | Cerca de Spawn-A - Center-A |
| Center-A | Spawn-A | Cerca del crossroads | Cerca de Spawn-A - Side-A |
| Side-B | Spawn-B | Cerca de la ciudad | Cerca de Spawn-B - Center-B |
| Center-B | Spawn-B | Cerca del crossroads | Cerca de Spawn-B - Side-B |

Todos son unidireccionales, usan rango `0.00-0.08`, peso `20` y tienen carretera a ambos extremos.

## Pozos de mana

| Zona | Pozo de mana obligatorio situado cerca de |
|---|---|
| Spawn-A | Spawn-A - Side-A |
| Side-A | Side-A - Center-B |
| Center-A | Spawn-A - Center-A |
| Spawn-B | Spawn-B - Side-B |
| Side-B | Side-B - Center-A |
| Center-B | Spawn-B - Center-B |
| Center | Side-A - Center; Side-B - Center; Center - Center-A; Center - Center-B |

Cada zona fuera de Center tiene un pozo de mana obligatorio junto a la salida indicada. Center tiene cuatro, uno junto a cada entrada directa. Center-A/B tambien contienen un Chapitel celestial; ver [contenido obligatorio](01-zones/07-mandatory-content.md).
