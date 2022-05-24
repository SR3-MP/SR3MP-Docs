# Functions

---

### Play2D
Return audio index.

```lua
Audio.Play2D(_audioId --[[ integer ]])
```

### GetId

```lua
local id = Audio.GetId(audioName --[[ string ]])
```

### IsPlaying

```lua
local isPlaying = Audio.IsPlaying(audioId --[[ integer ]])
```

### CreateMarker
Create a 2D marker in world space on top of a specific entity.

All markers ids:

![Mg5Ej6d](https://raw.githubusercontent.com/K3rhos/SR3MP-Docs/main/docs/images/Mg5Ej6d.jpg)

The last parameter has 3 modes: `1 = Normal, 2 = Show Distance, 3 = Wave Around`

```lua
UI.CreateMarker(entity --[[ integer ]], id --[[ integer ]], type --[[ integer ]])
```
