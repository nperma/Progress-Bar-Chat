# Progress-Bar-Chat
Dev Resources
---
Example Command:
```
/tellraw @s {"rawtext":[{"text":"cbar:Hello Everyone"}]}
```

Example ScriptAPI
```js
import { world } from "@minecraft/server";

world.afterEvents.playerSpawn.subscribe((e) => {
 e.player.sendMessage("cbar:Welcome to the Server")
})
```
