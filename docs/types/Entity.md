## Entity

### This is for methods that aren't already present in the API for one reason or another 
| Function | This-ref qualified | Arguments | Purpose |
| :-- | :-- | :-- | :-- |
| GetPropInt | Yes | int offset | Get property at self + `offset` |
| GetPropUint32 | Yes | int offset | Get property at self + `offset` |
| GetPropFloat | Yes | int offset | Get property at self + `offset` |
| GetPropBool | Yes | int offset | Get property at self + `offset` |
| GetPropVector | Yes | int offset | Get property at self + `offset` |
| GetPropString | Yes | int offset | Get property at self + `offset` |
| GetPropHandle | Yes | int offset | Get property at self + `offset` |
| SetPropInt | Yes | int offset, int value | Set property at self + `offset` to `value` |
| SetPropUint32 | Yes | int offset, uint32_t value | Set property at self + `offset` to `value` |
| SetPropFloat | Yes | int offset, float value | Set property at self + `offset` to `value` |
| SetPropBool | Yes | int offset, bool value | Set property at self + `offset` to `value` |
| SetPropVector | Yes | int offset, [Vector3](docs/types/../../Vector3.md) value | Set property at self + `offset` to `value` |
| SetPropString | Yes | int offset, String value | Set property at self + `offset` to `value` |


# Static methods

| Function | This-ref qualified | Arguments | Purpose |
| :-- | :-- | :-- | :-- |
| GetMinsMaxs | Yes | | Retrieve [Bounds](docs/types/../../Bounds.md) of mins and maxs |
| GetOrigin | Yes | | Retrieve [Vector3](docs/types/../../Vector3.md) of origin |
| GetSimTime | Yes | | |
| GetEffects | Yes | | |
| IsPlayer | Yes | | |
| IsWeapon | Yes | | |
| GetClientClass | Yes | | Retrieve [ClientClass](docs/types/../../ClientClass.md) of entity |
| IsDormant | Yes | | |
| GetIndex | Yes | | Internally inherited `Networkable` vftable index |