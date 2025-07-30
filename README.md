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

## Copyright
FTEQW: https://github.com/fte-team/fteqw  
Nuclide-SDK: https://code.idtech.space/vera/nuclide  
Half-Life and Other Games: https://code.idtech.space/fn  
