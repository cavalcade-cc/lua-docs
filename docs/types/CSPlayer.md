## CSPlayer

# Inherits [Entity](docs/types/../../Entity.md)

| Function | This-ref qualified | Arguments | Purpose |
| :-- | :-- | :-- | :-- |
| IsAlive | Yes | | Verify if player is alive |
| GetEyePosition | Yes | | Retrieve [Vector3](docs/types/../../Vector3.md) of eye position |
| GetBoundingBox | Yes | | Retrieve 2 member array of [Pair](docs/types/../../Pair.md) representing screen coordinates of bounding box |
| GetVelocityModifier | Yes | |  |
| IsImmune | Yes | |  |
| IsPlayerGhost | Yes | |  |
| IsScoped | Yes | | |
| HasHelmet | Yes | | |
| GetArmorValue | Yes | |  |
| CanFireShot | Yes | |  |
| IsEnemy | Yes | [CSPlayer](docs/types/../../CSPlayer.md) player | Verify if `player` is enemy, accounts for FFA deathmatch |
| GetDuckAmount | Yes | | |
| GetDuckSpeed | Yes | | |
| GetHealth | Yes | | |
| GetFlags | Yes | | Check [Flags](docs/enums/../../../enums/Flags.md) for available flags and use the `bit` library to check against the retrieved integer |
| GetTickbase | Yes | | |
| GetFallVelocity | Yes | | |
| GetViewOffset | Yes | | Retrieve [Vector3](docs/types/../../Vector3.md) of view offset |
| GetVelocity | Yes | | Retrieve [Vector3](docs/types/../../Vector3.md) of velocity |
| GetMoveType | Yes | | Check [MoveTypes](docs/enums/../../../enums/MoveTypes.md) for move types |
| GetEFlags | Yes | | |
| GetLifestate | Yes | | Check [LifeStates](docs/enum/../../../enums/LifeStates.md) for life states |
| GetTeam | Yes | | Check [Teams](docs/enum/../../../enums/Teams.md) for teams |
| GetHitboxPosition | Yes | [Hitboxes](docs/enum/../../../enums/Hitboxes.md) hitbox | Retrieve [Vector3](docs/types/../../Vector3.md) of hitbox |
| GetActiveWeapon | Yes | | Retrieve [Handle](docs/types/../../Handle.md) of active weapon |
| GetObserver | Yes | | Retrieve [Handle](docs/types/../../Handle.md) of player observer |