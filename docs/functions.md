# Functions

---

## Audio

#### __Audio.Play__
Return audio id.

```lua
local audioId --[[ integer ]] = Audio.Play(_audioCategory --[[ string ]], _audioClip --[[ string ]])
```

---

#### __Audio.Stop__

```lua
Audio.Stop(_audioId --[[ integer ]])
```

---

## UI

#### __UI.SetHUDActive__
Toggle game HUD visibility. (If game HUD is hidden, interaction features are locked)

```lua
UI.SetHUDActive(_toggle --[[ boolean ]])
```

---

#### __UI.IsHUDActive__
Return if game HUD is currently visible.

```lua
local isVisible --[[ boolean ]] = UI.IsHUDActive()
```

---

#### __UI.CreateMarker__
Create a 2D marker in world space on top of a specific entity.

All markers ids:

![Mg5Ej6d](https://raw.githubusercontent.com/SR3-MP/SR3MP-Docs/main/docs/images/Mg5Ej6d.jpg)

The last parameter has 3 modes: `1 = Normal, 2 = Show Distance, 3 = Wave Around`

```lua
UI.CreateMarker(_entity --[[ integer ]], _id --[[ integer ]], _type --[[ integer ]])
```

---

#### __UI.RemoveMarker__
Remove current marker on a specific entity if one exist.

```lua
UI.RemoveMarker(_entity --[[ integer ]])
```

---

#### __UI.AddObjectiveWaypoint__

```lua
-- [[ Add an objective waypoint to aiport position ]]

UI.AddObjectiveWaypoint(-998.621765, 18.168633, -944.803711)
```

---

#### __UI.RemoveObjectiveWaypoint__

```lua
UI.RemoveObjectiveWaypoint()
```

---

#### __UI.IsObjectiveWaypointExist__

```lua
local exist = UI.IsObjectiveWaypointExist()
```

---

#### __UI.GetObjectiveWaypointCoords__

```lua
local coords --[[ vector3 ]] = UI.GetObjectiveWaypointCoords()
```

---
