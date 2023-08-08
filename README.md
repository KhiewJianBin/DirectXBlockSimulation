# DirectXBlockSimulation
  Course Assignment Project in Singapore Polytechnic.
  
  A Grid layout based game rendered using DirectX 9 for Windows.
  
  <img src="https://user-images.githubusercontent.com/5699978/192391265-62c37d82-fd1f-419f-9059-716d3faacea3.png" width="700">
  
# Features
1. A Level Editor Mode to place Boxes as movement obstacles
2. A Game Mode to control a character with restricted grid movement
3. Multiple Camera Viewports and FreeLook/FreeCam Mode
4. Save Level as .txt
  
# Install
Require DirectX End-User Runtime Web Installer
No Other Installation Required. Just Git clone or direct download

## Usage
1. Run [My3DGame.exe](https://github.com/KhiewJianBin/DirectXBlockSimulation/blob/main/My3DGame.exe)

## Instructions

### Camera Controls

```
F1 - Top View
F2 - Front View 
F3 - Perspective View
F4 - Free Look - Changes To Camera Mode
```

### Editor Mode Controls
```
W - Move Selector up
S - Move Selector down
A - Move Selector Left
D - Move Selector Right
Q - Grid Level Increase
E - Grid Level Decrease
T - Lock on to Player
1-9 - Place Blocks
Backspace - Remove Block
```

### Game Mode Controls
```
W - Move Character Foward
S - Move Character Backward
A - Strafe Character Left
D - Strafe Character Right
Q - Rotate Player 90° left
E - Rotate Player 90° right
```

### Camera Mode Controls (FreeCam)
```
W - Forward 
S - Backward
A - Pan Left
D - Pan Right
Q - Elevate Up
E - Elevate Down
T - Lock on to Player
```

## Notes
- Purely keyboard controls. No mouse interactions
- Character can step up 1 block and fall multiple blocks


## Dev Notes
- Saves entire state of the level
- Load/Save format uses simple Char comparision
