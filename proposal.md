# Proposal

## What will (likely) be the title of your project?

Rise of the Dragon Slayer

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

An interactive 2D boss fight where the player takes on the role of a knight who must defeat a dragon to rescue a princess it has captured. 

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

The main focus of my project is the boss fight between the knight (the player) and the dragon. First, the game will load up to a menu screen with the title at the top where the player will press the "play" button. Upon clicking the button, the screen will transition into a dialogue (with visuals) about a dragon attacking a kingdom and taking the princess to its lair. The dialogue will also include the knight (the player) taking on the challenge of defeating the dragon and rescuing the princess. After the dialogue, the screen will transition to a map that shows the knight steadily progressing to the dragon's lair. After that, the boss fight begins. The fight will involve health bars of both player and dragon, fireball and swipe attacks that deal damage to the player, an attack button that shows up after dodging an attack from the dragon, and the dragon's attacks becoming faster once it reaches half of its health bar. The fight will also be 10 attack sequences long. If the player dies, the player will be sent to a death menu where they can press the "try again" button to try again. Once the dragon's health bar reaches 0, the dragon will let out one final roar before disappearing. After defeating the dragon, the player will be sent to a screen with the knight and the princess, where the princess thanks the knight for rescuing her. 

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

N/A

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

N/A

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

*A menu screen with the title and a working “Play” button 
*A short dialogue scene with visuals explaining the dragon’s attack, the princess’s capture, and the knight accepting the challenge
*A boss fight, with health bars for both the knight and the dragon, fireball and swipe attacks that damage the player, and a way for the player to attack the dragon

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

A playable game with a working menu, a dialogue scene, and a map screen leading into the boss fight, which includes health bars for both the knight and the dragon and fireball and swipe attacks, the dodge-then-attack button, the death menu, and the princess thanking the knight at the end. 

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

A complete, playable game that flows from the menu, beginning dialogue, and map into a 10-sequence boss fight with health bars, fireball and swipe attacks, a dodge-then-attack button, and a faster dragon at half health, that ends with the dragon’s final roar and the princess thanking the knight.

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

I’ll start by breaking the game into its screens (menu, dialogue, map, fight, ending) and learning how to build a scene manager, a variable that tracks which screen is active and runs only that screen’s code. After structuring how I want my game to run, I will look into coding platforms such as pygame and learn how to use them. I’ll also need to learn mouse and keyboard input for the Play and attack buttons, and how to draw text, images, and buttons on the screen. The boss fight is the hardest part, so I’ll build and test it early. For it, I’ll need to learn how to use timers to sequence the dragon’s 10 attacks, collision detection for the fireball and swipe, and a short reaction window after a dodge that reveals the attack button. I’ll also need to code health bars and a condition that speeds up the dragon at 50% health.

I’ll research sources for sprites, backgrounds, and sound, and check each license before using anything. Then I’ll build in order: menu and scene switching, dialogue and map, boss fight, and finally the ending and polish, so I always have a working game if time runs short. 
