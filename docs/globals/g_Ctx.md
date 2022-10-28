## g_Ctx

| Function | This-ref qualified | Arguments | Purpose |
| :-- | :-- | :-- | :-- |
| GetKeyState | No | int key, [KeyState](docs/../../enums/KeyState.md) state | Verifies if key state is `state` |
| GetKeyName | No | int key | Get String equivalent to `key` |
| GetMousePos | No | | Get mouse position as [Pair](docs/types/../../../types/Pair.md) |
| GetMapName | No | | Get current map name |
| GetSkyName | No | | Get current sky name |
| GetTime | No | | Get current delta time as float |
| RunJS | No | String js | Run JavaScript on current Panorama focus panel, on its base XML |
| RunJSForXML | No | String js, String xml | Run JavaScript on current Panorama focus panel, on `xml` |
| PushCallback | No | String [callback](docs/../../callbacks.md), Function function | Push function to be ran on callback |

# Tracking movement features
Only guaranteed to give current state in [CreateMove_Post](docs/../../callbacks.md).

The following functions are still part of the `g_Ctx` global's structure.

| Function | This-ref qualified | Arguments | Purpose |
| :-- | :-- | :-- | :-- |
| Jumpbugged | No | | |
| Autoducked | No | | |
| Longjumped | No | | |
| Ladderbugged | No | | |
| Ladderjumped | No | | |
| Edgebugged | No | | |
| Pixelsurfing | No | | |
| Minijumped | No | | |
| Staminahopped | No | | |
| Edgejumped | No | | |