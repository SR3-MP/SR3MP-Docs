## Client

- [Test](#test)

---

### Test
Adds an event handler to the current resource/scripting environment. Do note that, if the event is to be called from a remote source, it needs to be whitelisted with RegisterNetEvent (on the client) or RegisterServerEvent (on the server).

#### Syntax
```lua
Test(_eventName, _callback)
```
