# Roblox Loader Checker
---
## Library
```lua
local bLoader = loadstring(game:HttpGet("https://raw.githubusercontent.com/yellowsliper/loaderChecker/main/libu.so"))()
```
---
## Introduction
#### Cannot found key in `getgenv()`, `_G`, `shared` and the others
#### Custom Kick Message
#### Simple Using
---
## Example

Loader
```lua
local bLoader = loadstring(game:HttpGet("https://raw.githubusercontent.com/yellowsliper/loaderChecker/main/libu.so"))()
bLoader.createKey()

-- Your Script
```
Client
```lua
local bLoader = loadstring(game:HttpGet("https://raw.githubusercontent.com/yellowsliper/loaderChecker/main/libu.so"))()
bLoader.setKickMessage("No Key") --[[ Default Message: Detected Key bypass ]]
bLoader.checkKey()

-- Your Script
```
---
## Credit
[Discord](https://discord.com/users/756721913413369887)
