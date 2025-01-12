[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity

Objects:

UI:
The number of seeds planted.
The number of seeds remaining.
    - The UI changes every time a seed is planted

Player:
Movement around the map.
    - WASD keys
Planting the seeds.
    - Space Key
Press the space bar to plant the seed.

Seeds:
Remain on screen when the player plants them.
Only have up to 5.
    - -1 seed every time the player plants again


## Devlog
Prompt: Include the HW1 break-down exercise you wrote during the Week 1 - Lecture 2 (Jan 9) in-class activity (above). If you did not attend and perform this activity, review the lecture slides and write your own plan for how you believe HW1 should be built. If your initially proposed plan turned out significantly different than the activity answers given by Prof Reid, you may want to note what was different. Then, write about how the plan you wrote in the break-down connects to the code you wrote. Cite specific class names and method names in the code and GameObjects in your Unity Scene.


Write your Devlog here!
I plan to take each part of the break down and code it and hook it up into Unity to make sure that everything works one at a time. After I am able to accomplish that, I am going to make sure that the components and objects are able to work together. For example, I am going to first try to create the prefab for the seed, then code it to plant it, and then tie it together into changing the UI as I make that move. I started my coding with trying to set up the UI for the game because it felt like it would be the easiest to start on, especially because I understood how to implement the "_text" easily. After I ran it, I realized I needed to hook up the scripts to the gameobjects, so then I worked on that. I then worked on the movement for my character and instead of trying to make them move by clicking each letter, I wanted to do it by making it move both vertically and horizontally. I hooked up an int for each one and created a new Vector3 which would move both of them and translate it with moving * the speed * the delta time.


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
