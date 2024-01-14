# Cube Aside
<p align="center">
  <img src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/f37246d8-a4d8-40d9-a319-bb4388405353" alt="Icon" height="200">
  <img src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/40236b2b-9dd9-40de-9530-121f4d9d5bbd" alt="GPG header" height="200">
</p>

### About Game
The main idea of the game is to overcome the distance and avoid obstacles. To control the cube player needs to tap on the right or left side of the screen, as a result of which the cube will roll to the left or right line.

The game developed by [Aliaksandr Astapchyk](https://github.com/AlAstapchyk), published on Google Play in April 2022 and removed in October 2023.

### Loading
The cube does a roll for every 10% of the load.

<p align="center">
  <img alt="Game loading gif" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/9e6c7c2f-4fb5-481a-8e35-5833b3e7176e"/>
</p>

### Main menu
If the endless mode record is >50, displayed a text label with the record. Otherwise, shown "Tap to Play!". Start the game in endless mode by tapping any free area on the screen. In the main menu, navigate to the following sections:

- **Skins**: Choose cube, scope, ground, and colors for them and the background. Also, check how to unlock a particular skin.
<p align="center">
  <img width="720" alt="Skins 1" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/371f4403-0951-47ae-82c8-5b450fd7dc76">
  <img width="720" alt="Skins 2" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/e593cf8f-132b-4836-8954-9ae03dbb1fee">
</p>

- **Levels**: View the progress of passing all 10 levels, including the percentage completed and the number of level diamonds collected.
<p align="center">
  <img width="720" alt="Levels" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/63b098bf-3b68-4311-951b-f12114d2c7c7">
</p>

- **Shop**: Spend diamonds to acquire "Lucky Skin" or increase the starting distance. Every new purchase increases the price. Earn diamonds by watching ads, limited to 3 times every 15 minutes. Additionally, buy in-game currency (diamonds).
<p align="center">
  <img width="720" alt="Shop 1" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/1a099187-40e6-4632-ba3c-ff8fa9a1d96a">
  <img width="720" alt="Shop 2" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/b9c9578e-33bd-4769-8fb0-ffd5cd51874b">
</p>

- **Statistics**: Check 8 measurable parameters and access the leaderboard if GPG is connected.
<p align="center">
  <img width="720" alt="Statistics" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/be10ffed-7e5a-45a6-b55c-bc355c82fa9d">
</p>

- **Settings**: Control the volume of SFX, connect/disconnect the GPG, enable/disable the FPS counter, and check the current game version.
<p align="center">
  <img width="720" alt="Settings" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/afa4df18-0193-49b0-9074-6d615e024715">
</p>

### Game modes
- **Endless**: Continuous speed increasing on an ease-out graph with the generation of random diamonds and obstacles including multi-tiered ones. After death, the player can pay diamonds or watch ads at the first death to continue.
<div align="center">
  <img width="720" alt="Revival window" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/1b7f6efa-5a44-412d-ae04-6ac93dcee9fb">
  <div align="center"><em>The revival window after the first death</em></div>
</div><br>

- **Levels**: 10 Levels with 3 level diamonds on each. Each level is faster and longer than the previous one. A speed booster appears from the fifth level. For the first level completion additional diamonds are given based on which level it is in order.
<div align="center">
  <img width="720" alt="Completed level window" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/1b4e767c-f44a-4c5f-8136-e48399af7046">
  <div align="center"><em>Completed level window</em></div>
</div><br>

### Services
- GPGS for leaderboard
- AdMob and Unity Ads for advertisement
- Unity IAP for in-app purchases

### Saving method
Data saving in JSON with simple UTF-8 encryption.
<div align="center">
  <img width="651" alt="Settings data" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/88863179-83b3-449e-b7cf-ef0ac7c642d1">
  <div align="center"><em>Settings data</em></div>
</div>
    <br>
<div align="center">
  <img width="1097" alt="Player data" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/aa5d4127-d46f-46c6-9bad-9571e4dae1d7">
  <div align="center"><em>Player data</em></div>
</div>

### Resources
- Skins created using MagicaVoxel
- Sounds downloaded from [freesound.org](https://freesound.org/) and modified afterwards

### Optimization
- LeanTween as an animation engine
- Skins optimized using Mesh Combiner asset
- Baked light for static objects such as ground skins or obstacles
- TMP instead of embeded text labels
- Optimization for different screen resolutions and safe zones including 1:1 aspect ratio

<br>
<p align="center">
  <img width="503.8" alt="Square screen 1" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/cdf5400b-a845-40a9-97ff-9ca4c7f10391">
  <img width="503.8" alt="Square screen 2" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/c9f432fe-d16e-4f2e-bcca-e19d6590b384">
  <img width="1112" alt="Iphone 12 Pro Max screen" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/0c460204-ca86-4604-aa13-58cf5acef7cb">
</p>

### Other
- **Jump with random spin**: Cube jumps up and randomly spins in the air rotating on 1 or 2 random axes making 1 or 2 turns clockwise or counterclockwise. There is a chance to see a jump with no turns at all. This mechanic is used when selecting a skin, starting the game, and reviving after death.

<p align="center">
  <img alt="Game starting gif" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/c645e165-4a58-4cab-8f3e-1e54d534e72e">
</p>

- **Game menu**: If it is a level mode, the label with the level number is displayed, if it is not - "Random obstacles". Button to the main menu, continue, replay and SFX volume controller.

<p align="center">
  <img width="720" alt="Menu in level 9" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/763f7d29-eadd-47ff-b3ee-86861b16d9a6">
</p>

- **Spatial assistance**: The lane highlighting, aim and the pole are very useful for determining the position of the cube in space.

<p align="center">
  <img width="264" alt="Space assistance" src="https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/21c2d32a-cb6c-4ccf-9898-4e41963ff6ac">
</p>

### Screenshots from Google Play
![screenshot-1](https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/ce9e7221-a894-4bf2-b45d-dc84a4edc245)
![screenshot-2](https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/a6cf7e79-a556-4813-b34a-6ed247f35e5e)
![screenshot-3](https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/30518489-f7cf-42df-abd1-2dfd006e7ec6)
![screenshot-4](https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/02a4f796-3a19-4f77-9bb4-fedc8b5565a5)
![screenshot-5](https://github.com/AlAstapchyk/cube-aside-showcase/assets/104316850/04ff53dc-a167-413e-a05e-f6f3d0106efa)
