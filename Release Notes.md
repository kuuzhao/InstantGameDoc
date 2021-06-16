# 2019.4.9f1c103 Release Notes
## Improvements
 * Improves the speed to generate placeholder textures
 * Improves the speed and stability to upload streaming assets
 
## Changes
 * TMP: Add supports to stream font Texture generated from Text Mesh Pro
 * CCD: InstantGame now use InstantGame AppId instead of UPID and Coskey from CCD website
 * Animation: Add supports to stream Legacy Animation Clip
 * Pakcage: Migrates instantGame package to PackageManager as three packages: com.unity.autostreaming, com.unity.autostreaming.ccd and com.unity.instantgame;
 * Il2cpp: Add supports to enable strip engine code when using Il2cpp backendand. Enable strip engine code will reduce the size of libunity.so and move it from the shared engine package to game package. 

## Fixes
 * Scripting: Fix script missing caused by build instant game when set Managerd Striping Level to Medium/High.
 * Graphics: Fix UV error for sliced sprites
