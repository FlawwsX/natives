---
ns: PLAYER
---
## SET_PLAYER_LOCKON

```c
// 0x5C8B2F450EE4328E 0x0B270E0F
void SET_PLAYER_LOCKON(Player player, BOOL toggle);
```

```
Used to toggle player lock on to other peds whilst squaring up.
```

## Parameters
* **player**: The player ID to toggle the lock on for.
* **toggle**: Set to false to prevent lock on, set to false to allow for lock on.

## Examples

```lua
local plyId = PlayerId()
SetPlayerLockon(plyId, false)
```
