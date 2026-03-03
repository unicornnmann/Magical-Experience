# NOTE: Does not work on most executors.

Discord Community • [Invite](https://discord.gg/WeruZTAM)

```lua
local Module = {};

function Module.Execute(Url)
    local Success, Error = pcall(function()
        loadstring(Game:HttpGet(Url))();
    end)

    if not Success then
        return
    end
end

Module.Execute("https://raw.githubusercontent.com/unicornnmann/Magical-Experience/refs/heads/main/The%20Magical%20Unicorn");
```
