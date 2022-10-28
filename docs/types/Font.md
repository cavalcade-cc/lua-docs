## Font

| Constructor Argument | Description |
| :-- | :-- |
| path | Path where font (.ttf) is located |
| rasterization_size | Rasterization size for font atlas instance |
| style | [FontStyle](docs/enums/../../../enums/FontStyle.md) value |
| bold | Whether to apply artificial bolding to font or not |

| Function | This-ref qualified | Arguments | Purpose |
| :-- | :-- | :-- | :-- |
| GetTextSize | Yes | String string, float drawing_size | Retrieve Vector2 of width and height for `string` of `size`, safe to call in [Paint](docs/../../callbacks.md) |