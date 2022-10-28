## g_Render

| Function | This-ref qualified | Arguments | Purpose |
| :-- | :-- | :-- | :-- |
| Rect | No | float x, float y, float w, float h, float thickness, float rounding, [Color](docs/types/../../../types/Color.md) color | Draw rectangle |
| RectFilled | No | float x, float y, float w, float h, float rounding, [Color](docs/types/../../../types/Color.md) color | Draw rectangle fill |
| Circle | No | float x, float y, float thickness, float radius, [Color](docs/types/../../../types/Color.md) color | Draw circle |
| CircleFill | No | float x, float y, float radius, [Color](docs/types/../../../types/Color.md) color | Draw circle fill |
| PercentCircle | No | float x, float y, float thickness, float radius, float percentage, [Color](docs/types/../../../types/Color.md) color | Draw percentage circle |
| Line | No | float x, float y, float x1, float y1, float thickness, [Color](docs/types/../../../types/Color.md) color | Draw line |
| PolyLine | No | `<Array of Pair>` data, float thickness, [Color](docs/types/../../../types/Color.md) color | Draw connecting points |
| PolyFill | No | `<Array of Pair>` data, [Color](docs/types/../../../types/Color.md) color | Draw convex fill (closing) of connecting points |
| PolyLineMultiColor | No | `<Array of Pair>` data, float thickness, `<Array of `[Color](docs/types/../../../types/Color.md)`>` color | Draw connecting points. Expected that every data entry has a matching color entry |
| Text | No | float x, float y, String text, Font font, float size, [Color](docs/types/../../../types/Color.md) color | Draw text |
| GetScreenSize | No |  | Retrieve Vector2 of screen size |
| WOrldToScreen | No | Vector3 point | Retrieve Vector2 for point screen coordinates, fields are 0 if operation failed |