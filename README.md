# Roblox Loader Checker
---
## Library
```lua
local bLoader = loadstring(game:HttpGet("https://raw.githubusercontent.com/yellowsliper/loaderChecker/main/library.c"))()
```
---
## Introduction
#### Cannot found key in `getgenv()`, `_G`, `shared`
#### Custom Kick Message
#### Simple Using
---
## Example

Loader
```lua
local bLoader = loadstring(game:HttpGet("https://raw.githubusercontent.com/yellowsliper/loaderChecker/main/library.c"))()
bLoader.createKey()

-- Your Script
```
Client
```lua
local bLoader = loadstring(game:HttpGet("https://raw.githubusercontent.com/yellowsliper/loaderChecker/main/library.c"))()
bLoader.setKickMessage("No Key") --[[ Default Message: Detected Key bypass ]]
bLoader.checkKey()

-- Your Script
```
---
## Credit
[Discord](https://discord.com/users/756721913413369887)
