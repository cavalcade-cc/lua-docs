## Callbacks

| Callback | Arguments | Purpose |
| :-- | :-- | :-- |
| Paint |  | Place to call drawing methods of [g_Render](docs/globals/../../globals/g_Render.md), thread safe, all drawcalls are scheduled to pipeline for next frame |
| FrameStageNotify | [FrameStages](docs/enums/../../enums/FrameStages.md) stage |  |
| CreateMove_Pre | [UserCmd](docs/types/../../types/UserCmd.md) cmd | CreateMove before any prediction is ran |
| CreateMove_Post | [UserCmd](docs/types/../../types/UserCmd.md) cmd | CreateMove after prediction is ran, useful to emulate callbacks for [g_Ctx](docs/../globals/g_Ctx.md) movement states |
| LevelInitPreEntity |  | Can be useful for variable nullification |
| LevelInitPostEntity |  | Can be useful for variable nullification |
| LevelShutdown |  | Can be useful for variable nullification |
| FireEventIntern | [Event](docs/types/../../types/Event.md) event, bool is_server, bool is_client | Gets called everytime an event that you have a natural listener to is fired |
| ReportHit | [Vector3](docs/types/../../types/Vector3.md) point | Can be useful for hitmarker, fired on every hit local player lands (team/enemy) |