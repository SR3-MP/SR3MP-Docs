# Functions

---

## Audio

#### __Audio.Play2D__
Return audio index.

```lua
Audio.Play2D(_audioId --[[ integer ]])
```

#### __Audio.GetId__

```lua
local id = Audio.GetId(audioName --[[ string ]])
```

#### __Audio.IsPlaying__

```lua
local isPlaying = Audio.IsPlaying(audioId --[[ integer ]])
```

## UI

#### __UI.CreateMarker__
Create a 2D marker in world space on top of a specific entity.

All markers ids:

![Mg5Ej6d](https://raw.githubusercontent.com/K3rhos/SR3MP-Docs/main/docs/images/Mg5Ej6d.jpg)

The last parameter has 3 modes: `1 = Normal, 2 = Show Distance, 3 = Wave Around`

```lua
UI.CreateMarker(entity --[[ integer ]], id --[[ integer ]], type --[[ integer ]])
```

#### __UI.RemoveMarker__
Remove current marker on a specific entity if one exist.

```lua
UI.RemoveMarker(entity --[[ integer ]])
```

#### __UI.AddObjectiveWaypoint__

```lua
-- [[ Add an objective waypoint to aiport position ]]

UI.AddObjectiveWaypoint(-998.621765, 18.168633, -944.803711)
```

#### __UI.RemoveObjectiveWaypoint__

```lua
UI.RemoveObjectiveWaypoint()
```

#### __UI.IsObjectiveWaypointExist__

```lua
local exist = UI.IsObjectiveWaypointExist()
```

#### __UI.GetObjectiveWaypointCoords__

```lua
local coords --[[ vector3 ]] = UI.GetObjectiveWaypointCoords()
```

#### __UI.SetHUDActive__

```lua
UI.SetHUDActive(toggle --[[ boolean ]])
```
