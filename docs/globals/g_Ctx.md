## g_Ctx

| Function | This-ref qualified | Arguments | Purpose |
| :-- | :-- | :-- | :-- |
| GetKeyState | No | int key, [KeyState](docs/../../enums/KeyState.md) state | Verifies if key state is `state` |
| GetKeyName | No | int key | Get String equivalent to `key` |
| GetMousePos | No | | Get mouse position as [Vector2](docs/types/../../../types/Vector2.md) |
| GetMapName | No | | Get current map name |
| GetSkyName | No | | Get current sky name |
| GetTime | No | | Get current delta time as float |
| RunJS | No | String js | Run JavaScript on current Panorama focus panel, on its base XML |
| RunJSForXML | No | String js, String xml | Run JavaScript on current Panorama focus panel, on `xml` |
| PushCallback | No | String [callback](docs/../../callbacks.md), Function function | Push function to be ran on callback |