## This repository was moved to [git.ad5001.eu](https://git.ad5001.eu/Ad5001/UHC)

# Plugin completed ! Download it from [here](http://projects.ad5001.ga/UHC/download.php?d=UHC_v1.phar&n=UHC_v1.phar)

# UHC
 A highly customisable UHC plugin for Minecraft PE!

Welcome here, owner/player! You may know what UHC is but if not, read [this](wiki/What-is-UHC).    
This is a recreation of the well known UHC gamemode for Minecraft PE server softwares in PHP!    
### Why is this plugin better?
**This plugins allows:**
 - Creating simple but highly customisable UHC matchs
 - MultiWorld Compatibility
 - Scenarios! [What are scenarios](wiki/scenarios)    
    
Current complete features:
- [x] Playing UHC (damage without regen and golden apples)        
- [x] MultiWorld compatible     
- [x] Scenario working     
- **[here](https://github.com/Ad5001/SpectatorPlus)** Full spectator mode     
- [x] Events 
- [ ] API 3.0.0 Fix
     
# Config example:
```yaml
# Your lobby world
LobbyWorld: world
worlds:
   # Your UHC world
   uhc:
     name: uhc
     maxplayers: 8
     radius: 1000
     default_scenarios: [UHCWorldReseter]
```
