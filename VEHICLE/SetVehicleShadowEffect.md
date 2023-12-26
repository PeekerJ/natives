---
ns: VEHICLE
aliases: ["0xF0E4BA16D1DB546C"]
---
## _SET_VEHICLE_SHADOW_EFFECT

```c
// 0xF0E4BA16D1DB546C 0x5BD8D82D
void _SET_VEHICLE_SHADOW_EFFECT(Vehicle vehicle, int p1, int p2);
```

```
Adds some kind of shadow to the vehicle.
Uses range from 0 - 255
-1 disables the effect.
OLD NAME: DISABLE_VEHCILE_DYNAMIC_AMBIENT_SCALES
```

## Parameters
* **vehicle**: Target Vehicle
* **NaturalAmbientScale**: 0 - 255 (-1 to disable)
* **ArtificialAmbientScale**: 0 - 255 (-1 to disable)

