
ChatGPT
markdown
Copy code
# My Mac Setup

## Overview
- **Device:** M1 MacBook Air
- **Specs:** 8 Core CPU, 7 Core GPU

## Game Settings
- **V-Sync:** On
- **Resolution:** Usually 1680x1050 or 2560x1600
- **Graphics Settings:** As low as they can be

## Crossover 23.7 Settings
- **Windows:** Windows 7 64bit
- **Bottle:** DXVK/GPTK
- **M-SYNC:** On
- **E-SYNC:** On

## Important Notes
- **Thermal Throttling:** Expect it to occur.

## Testing

### Call of Duty (Any game)
- **Stability:** Not Stable
- **FPS:** Bad
- **Settings:** Maxed
- **Method:** Crossover (DXVK & D3DMetal), Mac App Store
- **Notes:** Very bad performance. Consider using Parallels.

### Simple Planes
- **Stability:** Very Stable
- **FPS:** Excellent
- **Settings:** Maxed
- **Method:** Rosetta (x64), Mac App Store
- **Notes:** Perfect FPS. Performance may vary based on the plane.

### Resident Evil: Village
- **Stability:** Stable
- **FPS:** Good
- **Settings:** Maxed
- **Method:** Native (ARM64), Steam
- **Notes:** Perfectly optimized. Stable at 30fps with maxed settings, 60fps+ on low settings.

### Minecraft: Java Edition
- **Stability:** Very Stable
- **FPS:** Excellent
- **Settings:** Maxed
- **Method:** Native (ARM64), Prism Launcher
- **Notes:** Perfect FPS with a well-optimized modpack.

### Sleeping Dogs: Definitive Edition
- **Stability:** Relatively Stable
- **FPS:** Ok
- **Settings:** Low
- **Method:** Crossover (DXVK & D3DMetal), Steam
- **Notes:** Looks ok with low settings. Reaches 60 fps with occasional small stutters.

### No Man's Sky
- **Stability:** Stable
- **FPS:** Ok
- **Settings:** Low
- **Method:** Native (ARM64), Steam
- **Notes:** Ok performance. Enable FSR or MetalFX for higher fps. May reach 60fps with settings tweaking until thermal throttling.

### Dying Light 1
- **Stability:** Relatively Stable
- **FPS:** Good
- **Settings:** Low
- **Method:** Crossover (D3DMetal), Cracked
- **Notes:** FPS occasionally drops but gameplay is good. Launches only with D3DMetal option checked.

### Grand Theft Auto V
- **Stability:** Very Stable
- **FPS:** Excellent
- **Settings:** Low
- **Method:** Crossover (DXVK & D3DMetal), Cracked
- **Notes:** FPS varies but generally stable. Resolutions may impact stutter, especially at 2560x1600.

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

### Installation
1. Download "GTA V.zip"
2. Unpack the .zip file
3. Place contents into your bottle or desired location
4. In Crossover, click on your bottle
5. Select "Wine Configuration"
6. Under "Libraries," input "dinput8.dll" as a new override for the library
7. Click add to apply the override
8. 
   This will make sure it loads Scripthook for the OpenAsi plugin so a corrupt error message doesn't come up and it actually loads properly.

   Don't trust me? Put your finger up your ass.


### Need-to-Know Info
