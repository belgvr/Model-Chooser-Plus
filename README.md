# Playermodel Chooser Plus

**Version**: 1.1  
**Author**: Ribas  
**Description**: A major improvement of AlienMario's 2020 Playermodel Chooser, offering expanded functionality, enhanced customization, and more efficient handling.
Credits to the original author and the original project, here: https://github.com/Alienmario/ModelChooser

## Features and Improvements

### Key Changes from AlienMario's 2020 Version:
- **Sound System Overhaul**:
  - Added support for **spawn sounds**, **kill sounds**, and **configurable sound delays**. Previously, only a limited set of sounds (hurt, death, etc.) were supported, and without control over sound delay or volume.
  - Added ConVars for greater control over sound behavior, including options for pitch, volume, and timing.
 
## ConVars and Their Functions
- **New convars for better fine tuning**
  - Below are the configuration variables (**ConVars**) used in **Playermodel Chooser Plus**, along with their default values and descriptions:

| **ConVar**                | **Default Value** | **Description**                                                                 |
|---------------------------|-------------------|---------------------------------------------------------------------------------|
| `sm_mcp_immunity`          | `1`               | Enables player damage immunity while selecting models.                           |
| `sm_mcp_autoreload`        | `1`               | Automatically reloads model list on map changes.                                 |
| `sm_mcp_playonview`        | `0`               | Plays a sound when a player views a model in the chooser.                        |
| `sm_mcp_playonselect`      | `0`               | Plays a sound when a player selects a model.                                     |
| `sm_mcp_playafterrespawn`  | `1`               | Continues playing a death sound after the player respawns.                       |
| `sm_mcp_jumpdelaymin`      | `0`               | Minimum delay (in seconds) between jump sounds.                                  |
| `sm_mcp_jumpdelaymax`      | `0`               | Maximum delay (in seconds) between jump sounds.                                  |
| `sm_mcp_hurtdelaymin`      | `1`               | Minimum delay (in seconds) between hurt sounds.                                  |
| `sm_mcp_hurtdelaymax`      | `1`               | Maximum delay (in seconds) between hurt sounds.                                  |
| `sm_mcp_mindmg`            | `15`              | Minimum damage required to trigger a hurt sound.                                 |
| `sm_mcp_hurtpitchmin`      | `99`              | Minimum pitch for hurt sounds.                                                  |
| `sm_mcp_hurtpitchmax`      | `101`             | Maximum pitch for hurt sounds.                                                  |
| `sm_mcp_jumppitchmin`      | `99`              | Minimum pitch for jump sounds.                                                  |
| `sm_mcp_jumppitchmax`      | `101`             | Maximum pitch for jump sounds.                                                  |
| `sm_mcp_jumpvol`           | `0.1`             | Volume for jump sounds.                                                         |
| `sm_mcp_hurtvol`           | `0.5`             | Volume for hurt sounds.                                                         |
| `sm_mcp_spawnvol`          | `0.5`             | Volume for spawn sounds.                                                        |
| `sm_mcp_killvol`           | `0.5`             | Volume for kill sounds.                                                         |
| `sm_mcp_deathvol`          | `0.5`             | Volume for death sounds.                                                        |

## Known Issues and Workarounds

### VMT and VMF Files Not Added to Download Table
There may be a bug where **VMT** and **VMF** files are not added to the download table automatically. This issue stems from limitations in my own knowledge and may not be fully resolved in this release.

**Workaround**:  
You can use the [**Directory Downloader plugin**](https://forums.alliedmods.net/showthread.php?p=2568881) as a workaround. This plugin allows you to list the required directories, ensuring that necessary files are downloaded properly by the client. Please refer to the link for further instructions on how to set it up.

### BMS (Black Mesa Source) Compatibility
The 2020 version supported **Black Mesa Source** (BMS) as a target game. However, I have not tested **Playermodel Chooser Plus** on BMS, and can only confirm functionality for **Half-Life 2 Deathmatch (HL2DM)** at this time. If you plan to use it for BMS, consider running your own tests, as there may be unforeseen issues.
