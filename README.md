# Playermodel Chooser Plus

**Version**: 1.1  
**Author**: Ribas  
**Description**: A major improvement of AlienMario's 2020 Playermodel Chooser, offering expanded functionality, enhanced customization, and more efficient handling.

## Features and Improvements

### Key Changes from AlienMario's 2020 Version:
- **Sound System Overhaul**:
  - Added support for **spawn sounds**, **kill sounds**, and **configurable sound delays**. Previously, only a limited set of sounds (hurt, death, etc.) were supported, and without control over sound delay or volume.
  - Added ConVars for greater control over sound behavior, including options for pitch, volume, and timing.
  
- **Improved Animation Handling**:
  - Added support for **dynamic playback rates** and **custom sequences** for different animations like **noclip** and **jump**.
  - AlienMario’s 2020 version had basic animations, but lacked the dynamic controls and extended animation support.
  
- **Model Locking and Unlocking**:
  - Introduced a more intuitive **model locking/unlocking** system with admin flag support. Previously, model accessibility was static and lacked flexibility.
  
- **Enhanced HUD and UI Elements**:
  - The HUD now provides more information, including model names, skin selection, and dynamic text updates. AlienMario’s version had minimal HUD customization.
  
- **New Admin Commands**:
  - Added commands for model locking and unlocking, expanding the ability to control player model availability on the server.

## Known Issues and Workarounds

### VMT and VMF Files Not Added to Download Table
There may be a bug where **VMT** and **VMF** files are not added to the download table automatically. This issue stems from limitations in my own knowledge and may not be fully resolved in this release.

**Workaround**:  
You can use the [**Directory Downloader plugin**](https://forums.alliedmods.net/showthread.php?p=2568881) as a workaround. This plugin allows you to list the required directories, ensuring that necessary files are downloaded properly by the client. Please refer to the link for further instructions on how to set it up.

### BMS (Black Mesa Source) Compatibility
The 2020 version supported **Black Mesa Source** (BMS) as a target game. However, I have not tested **Playermodel Chooser Plus** on BMS, and can only confirm functionality for **Half-Life 2 Deathmatch (HL2DM)** at this time. If you plan to use it for BMS, consider running your own tests, as there may be unforeseen issues.
