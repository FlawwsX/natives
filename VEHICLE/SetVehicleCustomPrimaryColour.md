---
ns: VEHICLE
---
## SET_VEHICLE_CUSTOM_PRIMARY_COLOUR

```c
// 0x7141766F91D15BEA 0x8DF9F9BC
void SET_VEHICLE_CUSTOM_PRIMARY_COLOUR(Vehicle vehicle, int r, int g, int b);
```

Sets the target vehicle's primary colours to the provided RGB value.

## Parameters
* **vehicle**: The target vehicle.
* **r**: RGB red value.
* **g**: RGB green value.
* **b**: RGB blue value.

## Examples

```lua
local vehicle = GetVehiclePedIsIn(PlayerPedId(), false) -- Grabbing the vehicle the player is sat in.
SetVehicleCustomPrimaryColour(vehicle, 255, 0, 0) -- Setting the colour to red using RGB values.
```
