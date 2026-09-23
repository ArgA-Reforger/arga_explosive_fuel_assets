# Arga Explosive Fuel Assets

Based in SH EXPLOSIVE FUEL ASSETS

Workshop: https://reforger.armaplatform.com/workshop/6A6ADA80E3924FC3-ArgaExplosiveFuelAssets

- [English](#english)
- [Español](#español)

## English

A rebalanced version of SH Explosive Fuel Assets that makes fuel-related props explode in a more realistic and predictable way. Damage values were calibrated in-game from measured 5.56 hit counts instead of nominal ammo values.

### What changed

**Pressurized gas (explodes from any bullet)**

- Small gas cylinders (GasTank_01): ~5 hits.
- Large gas cylinders (GasTank_02): ~10 hits.
- Gas welder: ~10 hits. Its vanilla damage threshold was removed, so regular rounds now affect it.

**Liquid fuel (only tracer or incendiary rounds)**

- Fuel barrels: ~10 tracer hits. Regular ball ammo does nothing.
- Fuel pallets (including camo US/USSR and cluttered variants): ~10 tracer hits.
- Fuel stations: ~10 tracer hits. The leftover wreck prefab is no longer spawned after the explosion.

**Left vanilla**

- Empty metal barrels and jerrycans keep their vanilla behavior.

**Explosions and chain reactions**

- All fuel props also react to nearby explosions: grenades, explosives, HE rounds and shrapnel damage them heavily, regardless of ammo type.
- An exploding barrel or pallet can set off other fuel props around it, causing chain reactions.

### Notes

- Overrides vanilla prefabs, so it works on any map and with existing scenarios.
- Hit counts are approximate and measured with 5.56 ammo; heavier calibers will need fewer hits.

## Español

Una versión rebalanceada de SH Explosive Fuel Assets que hace que los props relacionados con combustible exploten de forma más realista y predecible. Los valores de daño se calibraron en el juego a partir de la cantidad de impactos de 5.56 medidos, en lugar de los valores nominales de la munición.

### Qué cambió

**Gas presurizado (explota con cualquier bala)**

- Garrafas de gas chicas (GasTank_01): ~5 impactos.
- Garrafas de gas grandes (GasTank_02): ~10 impactos.
- Soldadora a gas: ~10 impactos. Se eliminó su umbral de daño vanilla, por lo que ahora la munición común la afecta.

**Combustible líquido (solo munición trazadora o incendiaria)**

- Barriles de combustible: ~10 impactos de trazadora. La munición común no les hace nada.
- Pallets de combustible (incluidas las variantes camo US/USSR y cluttered): ~10 impactos de trazadora.
- Estaciones de combustible: ~10 impactos de trazadora. Ya no aparecen los restos después de la explosión.

**Sin cambios respecto a vanilla**

- Los barriles metálicos vacíos y los bidones mantienen su comportamiento vanilla.

**Explosiones y reacciones en cadena**

- Todos los props de combustible también reaccionan a explosiones cercanas: granadas, explosivos, proyectiles HE y esquirlas les hacen mucho daño, sin importar el tipo de munición.
- Un barril o pallet que explota puede detonar otros props de combustible cercanos y provocar reacciones en cadena.

### Notas

- Sobrescribe prefabs vanilla, por lo que funciona en cualquier mapa y con escenarios existentes.
- La cantidad de impactos es aproximada y se midió con munición 5.56; calibres más pesados necesitan menos impactos.
