# Games automatic builder (from Nuclide SDK)
This project will automate the compilation of games or engines built using QuakeC language and the Nuclide SDK, and automatically generate and publish .pk* files. (This does not include any game resource files; please extract those from legitimate games.)  

## How to play it
**Normal Steps**:  
- **Step 1**: Get [FTEQW](https://www.fteqw.org/) for your system os.
- **Step 2**: Copy your game directory (but not the root directory; you don't need any files other than those for the game and mods).
    - For example, valve, to FTEQW (get it yourself if you don't have it).
- **Step 3**: Run `fteqw -halflife -game valve` to launch the game.
    - Linux: `./fteqw -halflife -game valve`
    - Windows: `fteqw.exe -halflife -game valve`
    
**They Hunger**:  
- **Step 1**: Get FTEQW and valve(nuclide)
- **Step 2**: Get They Hunger https://code.idtech.space/fn/hunger/archive/master.zip
- **Step 3**: Move They Hunger mod folder to FTEQW, and unzip master.zip to They Hunger mod folder.
- **Step 4**: Run `fteqw -halflife -game hunger` to launch the mod.

## Games list
| Games/Mods | Codename | Build Status | Version | Fork | Workflow |
|-----------|-----------|-----------|-----------|-----------|-----------|
| [Half-Life](https://code.idtech.space/fn/valve) | valve | ✅ | Latest | master | Normal |
| [Half-Life 2](https://code.idtech.space/fn/hl2) | hl2 | ✅ | Latest | master | Normal |
| [Team Fortress Classic](https://code.idtech.space/fn/tfc) | tfc | ❌ | Latest | master | Normal |
| [Gunslinger Saga](https://code.idtech.space/fn/rewolf) | rewolf | ❌ | Latest | master | Normal |
| [Counter-Strike 1.5](https://code.idtech.space/fn/cstrike) | cstrike | ✅ | Latest | master | Normal |
| [The Specialists](https://code.idtech.space/fn/ts) | ts | ❌ | Latest | master | Outdated |
| [Opposing Force](https://code.idtech.space/fn/gearbox) | gearbox | ❌ | Latest | Develop | Outdated |
| [Scientist Hunt](https://code.idtech.space/fn/scihunt) | scihunt | ✅ | Latest | master | Normal |
| [Counter Strike Source](https://code.idtech.space/fn/css) | css | ✅ | Latest | master | Normal |

## Copyright
FTEQW: https://github.com/fte-team/fteqw  
Nuclide-SDK: https://code.idtech.space/vera/nuclide  
Half-Life and Other Games: https://code.idtech.space/fn  
