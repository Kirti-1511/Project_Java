In a text adventure game, the central character is the Adventurer, which is an object representing the human player. You need this object because you need to keep track of where the player is, what the player is holding, and anything else you need The adventurer plays the game by typing in commands. Commands consist of one or two words (more than two is too much work). 
When the player moves to a new location, the response should usually be a full description of the newly- entered Room. Program Details An adventure game consists of: 
(1) A TextAdventure class. 
    This class: 
    Contains the main method used to start the game. 
    Talks to the AdventureModel and to the Adventurer classes, as needed. 
(2) An AdventureModel class. 
    This class: • Creates the Rooms, the Things, and the Adventurer. • Connects the Rooms with "paths" to other Rooms. • Places Things in the Rooms. • Places the Adventurer in some Room. • Accepts commands from the player, and executes them. o As commands are entered, they should be copied to the main text area. o The method that executes commands should return a String to be displayed in the main text area. 

(3) An Adventurer (the human player). 
    An adventurer has: 
    A location (some room). 
    An inventory (the things being carried). When the player executes the “take thing” command, the item should be added to the inventory. An adventurer can: 
    Move from room to room. 
    Carry a number of objects. 
    Pick up, drop, look at, and use various objects.

(4) Some number of Rooms. 
   A room has: 
      A name. 
      A description, possibly several sentences long. 
      Contents: the things in the room. 
      Exits: paths to other rooms (usually some of north, south, east, and west). 
      Some number of Things. 
A thing has: 
      A name § If some of your Things have multi-word names, such as "firebreathing dragon" or "that thing that your aunt gave you that you don't know what it is", then you might want to give your Things both a full name and a one-word name. 
      A description, to be shown when the adventurer "looks" at it. 
      One or more methods for using the Thing. You can have a multi- purpose use verb, or you can make up your own verbs (for instance, drink water or pour water), which determines what the thing does when the adventurer tries to use it. 
      For simplicity, we will say that the adventurer can only use things being carried (in the inventory) 
      Whether "using" a thing does anything or not (or exactly what it does) can depend on what room it is in, what other things are in the room or in the inventory, or any other conditions you can think of. Your assignment is to write an adventure game with your group. 
It should have: 
      A general location (battlefield, outer space, etc.) 
      At least 10 rooms 
      An inventory for the player to store items 
      At least 3 examples of Inheritance 
      At least 2 examples of Overridden Methods 
      At least 1 example of Polymorphism (note it in a code comment so I can see you understand it) 
      Be sure only the minimum methods are public; most of your methods and variables should be private 

Note:-

This is where you will describe the available commands and anything else necessary for the user to play your game. The theme of the game, and the goal of the game, is up to you. So that your adventure game is not too difficult to grade, please: 

1. Don't let the player "die" or otherwise get into a situation from which there is no possibility of winning the game. 

2. Include a walkthrough (in a file named README.txt) to tell me how to play your game to a successful completion


