### DIPgroup1

since the game project is too big to be uploaded onto GitHub, our group uploaded packages that include our change and import them into our local project, follow the steps to set up

# Please read the following steps to set up the game in a new project in Unity
1. create a new unity project 2D built-in-pipeline
2. open the project and import all needed packages
3. go to unity package manager, change in-project to unity registry, search and download "AI navigation" and "Input system" packages
4. go to project settings -> player -> others -> active input handling, change it to both to use the new input system
5. layering: create 2 customer layers, "counters" and "staffbot"
6. all counters, including customers should be set the "counters" layer
7. the staffbot in level2scene should be set to "staffbot" layer
8. under gameobject staffbot -> staffbot controller script, set "Layer Mask Counters" to "Counters" 
9. under gameobject player -> player controller script, set "Layer Mask Counters" to "Counters"
10. under gameobject player -> player controller script, set "Layer Mask Staffbots" to "staffbot"
11. file -> build settings, open all scenes and click add open scenes, then click build and run
12. You are good to go! 


# OVERALL TO DO LIST:

- [x] 1. Half 2D board (fake 3D grid board) -> continuous movement 
                                      -> coordination based interactive range of the object
                                      -> use collisions box (use placeholders before design team gives us the board)
- [x] 2. Game manager -> level, timer, money count, ingredients available, order requests 
- [x] 3. Player controler -> directional button, keyboard
- [x] 4. More interactions with objects (eg. tables)  -> lvl 2
- [x] 5. Object class (eg. dish class -> actions related to dishes) 

- [x] 6. Add functionality to the map (add clickable button to each scene)
- [x] 7. Handle the trivia pop-up (make it clickable for answer)

EXTRA: power-ups -> additional button for speed vs. manually increase speed 


- [x] by Week 3: player movement, blockage will stop the player (Yuheng)
- [x] by Week 7: random customer-random movement (Rebeca)

