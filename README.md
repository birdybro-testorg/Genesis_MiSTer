# Genesis MiSTer

This is a port of the [Sega Genesis/MegaDrive](https://en.wikipedia.org/wiki/Sega_Genesis) clone **[FPGAGen by Torlus](https://github.com/Torlus/fpgagen)** to the **[MiSTer](https://mister-devel.github.io/MkDocs_MiSTer/)** platform.


## Install
1. Copy all  `.rbf`  files to the root folder of an **SD Card**.
2. Place your **ROM**s into the  `Genesis`  folder.  
    *Allowed Formats:*  
    <kbd> .BIN </kbd> <kbd> .GEN </kbd> <kbd> .MD </kbd> 


## Hotkeys
The following hotkeys reset the region.

| Key | Region | Type
|:---:|:------:|:----:
| <kbd> F1 </kbd> | ***JP*** | ***NTSC***
| <kbd> F2 </kbd> | ***US*** | ***NTSC***
| <kbd> F3 </kbd> | ***EU*** | ***PAL***


## Auto Region Selection
There are two methods of region detection.

### Header Based
- The header of the ROM may include [one or several region codes](https://plutiedev.com/rom-header#region).
- The region will be chosen depending on the priority option in the On-Screen Display.

### File Extension
`BIN`  🠖  **JP**  
`GEN`  🠖  **US**  
`MD`   🠖  **EU**


## More Features
- **Option to choose between `YM2612` and `YM3438` mode**  
    *Changes Ladder Effect behavior.*
    
- **Composite Blending**  
    *Smooth dithering patterns in games.*
    
- **Audio Filters**:  
    <kbd> Model 1 </kbd> <kbd> Model 2 </kbd> <kbd> Minimal </kbd> <kbd> No Filter </kbd>
    
- **Sprite Limit**  
    *Enables more sprites.*
    
- **Multitaps**:  
    <kbd> Team player </kbd> <kbd> J-Cart </kbd> <kbd> 4-way </kbd>
    
- **CPU Turbo**  
    *Mitigates slowdowns.*
    
- **SVP Chip**  
    *Virtual Racing*
