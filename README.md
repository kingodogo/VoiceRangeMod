# VoiceRangeMod

## Overview
**VoiceRangeMod** enhances REPO's in-game voice chat by increasing the distance at which player voices can be heard.  
It also adds a **Hold-to-Talk (Walkie-Talkie)** mode for better control.

- Extend the range of voices beyond the normal in-game limit  
- Supports configurable distance multipliers  
- Fully adjustable via config file  

---

## Installation
1. Download the latest release of **[VoiceRangeMod](https://github.com/kingodogo/VoiceRangeMod/releases)**.  
2. Install **[BepInEx 5.4.21](https://thunderstore.io/package/BepInEx/BepInExPack/)** for REPO.  
3. Extract the contents of the `.zip` into your `BepInEx/plugins/` folder inside the REPO game directory.  
4. Launch the game once to generate the configuration file.  

---

## Hotkey
- **R** → Activates Walkie-Talkie mode (talk to anyone, no matter the distance)  
- Can be changed in the config file.

---

## Configuration
Config file location:  
 - **BepInEx/config/com.Kingo.voicerange.cfg**
 
Available parameters:
1. **RangeMode** → Options: `Normal`, `Far`, `VeryFar`  
   - `Normal` → Default range (1x)  
   - `Far` → 1.5x range  
   - `VeryFar` → 2x range  
2. **TalkKey** → Change the key used for Hold-to-Talk mode  
3. **HoldToTalk** (`true/false`) → Enable or disable Walkie-Talkie mode  

---

## Support
- Report bugs or suggest new features here:  
  👉 [GitHub Issues](https://github.com/kingodogo/VoiceRangeMod/issues)
