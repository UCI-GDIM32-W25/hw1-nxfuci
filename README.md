[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity
Objects:

UI:
- The number of seeds planted.
- The number of seeds remaining.
- The UI changes every time a seed is planted

Player:
- Movement around the map.
    - WASD keys
- Planting the seeds.
    - Space Key
- Press the space bar to plant the seed.

Seeds:
- Remain on screen when the player plants them.
- Only have up to 5.
    - -1 seed every time the player plants again

## Devlog
I plan to take each part of the break down and code it and hook it up into Unity to make sure that everything works one at a time. After I am able to accomplish that, I am going to make sure that the components and objects are able to work together. For example, I am going to first try to create the prefab for the seed, then code it to plant it, and then tie it together into changing the UI as I make that move. I started my coding with trying to set up the UI for the game because it felt like it would be the easiest to start on, especially because I understood how to implement the "_text" easily. After I ran it, I realized I needed to hook up the scripts to the gameobjects, so then I worked on that. I then worked on the movement for my character and instead of trying to make them move by clicking each letter, I wanted to do it by making it move both vertically and horizontally. I hooked up an int for each one and created a new Vector3 which would move both of them and translate it with moving * the speed * the delta time.

To start planting the seeds, I knew that I first needed to intergrate a method in which would activate when placing a key which is why I used "GetKeyCode". We start off with 5 seeds, and we want to go all the way down to 0 and not keep going which is why we do it > 0. Then, I instantiated the plant prefab that I made to place it when I click space. Then, you implement "Quaternion.identity" into it for the prefab to spawn on your position without having any sort of rotation. Lastly, I then implemented gettning rid of one seeds remaining, and add one seeds planted for each time space is clicked.

## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites

## Prof comments
Thank you for connecting the break-down to your code!

Please consider formatting your break-down activities with the hyphen '-' symbol as suggested above, and remove the prompts. This will make it a lot easier for me to read. See the [README formatting guide here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
