---
ns: CAM
---
## IS_CAM_INTERPOLATING

```c
// 0x036F97C908C2B52C 0x7159CB5D
BOOL IS_CAM_INTERPOLATING(Cam cam);
```

## Examples
```lua
SetCamActiveWithInterp(cam2, cam1, 700, 450, 450)
repeat
  Wait(0)
until not IsCamInterpolating( cam2 )
```

## Parameters
* **cam**: Camera handle to check is interpolating

## Return value
Returns whether or not the specified camera is interpolating.
