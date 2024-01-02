# My Mac Setup

## Overview
- **Device:** M1 MacBook Air
- **Specs:** Base Model, 7 Core GPU

## Game Settings/Notes
- **V-Sync:** On
- **Resolution:** Usually 800x600 (V Low res), 1680x1050 (Mid res) or 2560x1600 (High res)
- **Graphics Settings:** As low as they can be or depending on the game and fps I can test with better settings
- **FPS:** Bad: 10-20, Good: 30-40, Excellent: 50-60
- **Stability:** Not Stable: Stuttery mess, Stable: Some stutters, Very Stable: Buttery

## Crossover Settings
- **Windows:** Windows 7 64bit
- **Bottle:** DXVK/GPTK
- **M-SYNC:** On

- ## Parallels Settings
- **Windows:** Windows 11 Pro
- **CPU:** 2/4 Cores, Depends
- **RAM:** 2/4 GB, Depends


## Important Notes
- **Thermal Throttling:** It will happen on my mac, so keep that in mind, these are mostly all burst tests

## Testing

### Borderlands 2
- **Stability:** Stable
- **FPS:** Excellent
- **Settings:** Medium
- **Method:** Native (x64) Steam
- **Notes:** Good game, works well

### Art of Rally
- **Stability:** Stable
- **FPS:** Excellent
- **Settings:** Medium
- **Method:** Native (x64) Steam
- **Notes:** Ok, not bad, but the games not really fun at all

### Absolute Drift 
- **Stability:** Stable
- **FPS:** Excellent
- **Settings:** Maxed
- **Method:** Native (x64) Steam
- **Notes:** Ok, not bad, but the games not really fun at all

### Combat Master
- **Stability:** Very Stable
- **FPS:** Excellent
- **Settings:** Low
- **Method:** Native (ARM64) Steam
- **Notes:** Perfect, buttery. Max Resolution

### Call of Duty (Any game)
- **Stability:** Not Stable
- **FPS:** Bad
- **Settings:** Low
- **Method:** Crossover (DXVK & D3DMetal), Mac App Store
- **Notes:** Very bad. Don't even try it. Would work better in parallels but it would still be bad, trust me

### Simple Planes
- **Stability:** Very Stable
- **FPS:** Excellent
- **Settings:** Maxed
- **Method:** Rosetta (x64), Mac App Store
- **Notes:** Perfect FPS with high res. Depends on the plane you choose and the amount of 'parts' it has

### Resident Evil: Village
- **Stability:** Stable
- **FPS:** Good
- **Settings:** Maxed
- **Method:** Native (ARM64), Steam
- **Notes:** Perfectly optimized. Stable at 30fps with maxed settings, high res and upscaling, 60fps+ on low settings. This is how a good game should be! My theory is that it is designed for a iPhone and then ported over to mac with higher graphic settings

### Minecraft: Java Edition
- **Stability:** Very Stable
- **FPS:** Excellent
- **Settings:** Maxed
- **Method:** Native (ARM64), Prism Launcher
- **Notes:** Perfect fps with Fabulously Optimised modpack. Nothing more to say, High res

### Sleeping Dogs: Definitive Edition
- **Stability:** Relatively Stable
- **FPS:** Ok
- **Settings:** Low
- **Method:** Crossover (DXVK & D3DMetal), Steam & Native (x64)
- **Notes:** Looks ok with low settings. Reaches 60 fps and sometimes dips with occasional small stutters. Crossover works better than native because of native using outdated OpenGl. Mid res

### No Man's Sky
- **Stability:** Stable
- **FPS:** Ok
- **Settings:** Low
- **Method:** Native (ARM64), Steam
- **Notes:** Ok. I would expect more from a native game like this. High res and make sure to Enable FSR or MetalFX for higher fps. Doesn't look magnificent. Can reach 60fps with tweaking settings until thermal throttling comes over for dinner

### Dying Light 1
- **Stability:** Relatively Stable
- **FPS:** Good
- **Settings:** Low
- **Method:** Crossover (D3DMetal), Cracked
- **Notes:** FPS sometimes goes down to around 55-ish but gameplay is good. Not many stutters. Only Launches with D3DMetal option checked. Mid res

### Grand Theft Auto V
- **Stability:** Very Stable
- **FPS:** Excellent
- **Settings:** Low
- **Method:** Crossover (DXVK & D3DMetal), Cracked
- **Notes:** FPS can shoot up to 120 in some areas while it can go down to 60-80 in city areas. The high res has small stutters which is still playable at around 45fps in city areas. The lite version of GTA-V has a very big impact on stutter which is negligble now and helps boost the fps by a considerable amount. By upping some settings you can still gain 60fps with some drops

## GTA-V + Resized + Lite

### Overview
- **What is it?** Modded GTA-V with GTA-V Resized from [gta5-mods.com](https://www.gta5-mods.com/misc/gta-v-re-sized).
- **Cons:** 
  - Radio won't work
  - Weapon wheel glitches
  - Some missions may not work
  - Prologue's audio won't work
  - Online play not available
- **Pros:** 
  - Reduced size (45gb)
  - Faster loading
  - Significant FPS boost due to removed DLCs and GTA-V resized installation

### Installation - NOT WORKING AS OF NOW
1. Download "GTA V.zip"
2. Unpack the .zip file
3. Place contents into your bottle or desired location
4. In Crossover, click on your bottle
5. Select "Wine Configuration"
6. Under "Libraries," input "dinput8.dll" as a new override for the library
7. Click add to apply the override
8. Launch GTA V
   This will make sure it loads Scripthook for the OpenAsi plugin so a corrupt error message    doesn't come up and it actually loads properly

   Don't trust me? Put your finger up your ass.


### Need-to-Know Info
