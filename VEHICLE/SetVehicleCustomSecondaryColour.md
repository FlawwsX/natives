---
ns: VEHICLE
---
## SET_VEHICLE_CUSTOM_SECONDARY_COLOUR

```c
// 0x36CED73BFED89754 0x9D77259E
void SET_VEHICLE_CUSTOM_SECONDARY_COLOUR(Vehicle vehicle, int r, int g, int b);
```

Sets the target vehicle's secondary colours to the provided RGB value.

## Parameters
* **vehicle**: The target vehicle.
* **r**: RGB red value.
* **g**: RGB green value.
* **b**: RGB blue value.

## Examples

```lua
local vehicle = GetVehiclePedIsIn(PlayerPedId(), false) -- Grabbing the vehicle the player is sat in.
SetVehicleCustomSecondaryColour(vehicle, 0, 179, 255) -- Setting the colour to blue using RGB values.
```
