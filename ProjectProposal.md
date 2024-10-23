# Project Proposal

## Identifying And Defining

### Brainstorming
|Game (Type)|P|M|I|
|--|--|--|--|
|Open World RPG|User Freedom|Very complicated to create|Quests and adventures|
|First Person Shooter|immersive and engaging|Motion sickness|A variety of weapons|

### Identifying a Need
__Need:__ My game aims to build up curiosity in young children through exploration and interesting questlines such as collecting items and finding characters.\
__Problem Statement:__ Young children need engaging and fun games to develop their curiosity. A fun RPG game that lets players roam and explore a world. It also includes fun and interactive quests that children are able to complete.\
__Skill Development:__ To develop the skills needed to create this game, I will follow the Unity Learn tutorial: https://learn.unity.com/project/creator-kit-rpg?uv=2021.3

### Requirements Outline
__Inputs:__ My game will need to track keyboard inputs such as WASD or arrow keys to track character movement. It also needs to track mouse movements and clicks to identify the decisions made by the player.\
__Processing:__ My program will check for interactions between the character/player and NPCs. It will also check if characters enter/exit building and modify the background accordingly.\
__Outputs:__ The game will display character, active quests and background such as building, grass or fences. It will also display character dialogue when interacting with a character. It will also display information to the user when the character reaches a specific location.\
__Transmission:__ There will be no need for data transmission as it is just a solo RPG game. It is will also be able to be played offline.\
__Storage:__ User progress will be stored and saved locally so the user can safely quit and and log off without losing any progress.\

### Functional Requirements
__User Interaction:__ The user will intereact with the system via mouse movevments, clicking, and keyboard commands. The user will be able to move the character, pick up items, select options as well as interact with NPCs. For example, WASD will move a character around and clicking on a NPC will begin an interaction with it, whether it is displaying a quest or adding to the story.\
__Core Gameplay or Simulation Mechanics:__ My game will need movement in NSEW. This is completed by using the WASD keys. Combat will be available when encoutering enemies. When a weapon is equipped, clicking will cause a slash, killing the enemy. Quests, such as object collection will also be part of the game. Text boxes will show when a user interacts with a NPC, displaying a quest and the option to accept and decline.\
__Scoring and Feedback:__ If a user tries to enter a restricted area or a area they have not unlocked, warning messages will appear, warning the user to leave the said area.\
__Level Progression or Simulation Stages:__ New levels will be available to the user when they complete the quest that allows them to access the new area, giving them new items and quests.\
__Saving and Loading Data:__ User progress will auto save at even intervals. When booting up a game, it will automatically load the latest save. User can also manually save. All saves will be done locally.\

### Non-Functional Requirements
__Performance Requirements:__ The game should load under 10 seconds and respond to user inputs instantly without any lag. FPS will depend on the components of the user's computer.\
__Usability Requirements:__ The game's UI will display play, saves and tutorial buttons. The tutorial will include a list of keybinds, and guides on how to complete quests and the games combat system, giving them knowledge on all the machanics of the game.\
__Compatibility Requirements:__ My game can only be run on PC. Mobile and web browsers will be unavailable.\
__Scalability Requirements:__ The game should be able to scale to include new levels, items and game machanics without having a drop in performance.
__Reliability and Availability:__ The system should be available 90% of the time. It does not need to handle network disruptions as it runs offline. In the case of a crash, the game will load back to its latest save, whether made by the user of automatically.

### Consideration of Social and Ethical Issues
__What is Equity and Accessibility:__ Equity recognizes that different circumstances require different resources and opportunities to achieve an equal outcome. Accessibility means the quality of being easily reached, entered, or used by people who have a disability
