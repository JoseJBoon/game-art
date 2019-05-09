---
layout: default
---

# Game world Dimension - Space Gravity

## PHYSICAL DIMENSION

### 1. Does my game require a physical dimension? What is it used for? Is it an essential part of gameplay or merely cosmetic?
Mass & Forces; Spacecraft has his own gravity; this gravity could change during the course of the game. Certain objects need to heavier so they can’t be moved easily by the player alone.

### 2. Leaving aside issues of implementation or display, how many imaginary spatial dimensions does my game require? If there are three or more, can objects move continuously through the third and higher dimensions, or are these dimensions partitioned into discrete “layers” or zones?
The player can move in a 2D environment, but there will be use of parallax backgrounds and/or different segments of the levels on different layers to give the game a more 3D feel to it.

### 3. How big is my game world, in light-years or inches? Is accuracy of scale critical, as in a football game, or not, as in a cartoon-like action game?
The game world will exist out of one or more spacecrafts; These spacecrafts are meant to be able to sustain a small human society between 100 and 1000 humans; Scale is not critical, but the player does need to get the illusion that the spacecrafts are large;

### 4. Will my game need more than one scale, for indoor versus outdoor areas, for example? How many will it actually require?
Some level segments can be seen from the current segment the player is on. These level segments need to be scaled down.

### 5. How am I going to handle the relative sizes of objects and people? What about their relative speeds of movement?
In game the level segment the player is everything will be scaled based on the Unity Unit. This unit size is a 100x100 pixels and represents 1 meter. Other viewable segments that are in the background will be scaled down to create depth. The speed of objects don’t change unless they’ve different gravity settings.

### 6. How is my world bounded? Am I going to make an effort to disguise the “edge of the world,” and if so, with what? What happens if the player tries to go beyond it?
Within the spacecraft the player will be bounded by walls, but outside the player will either die or forced back if he goes beyond a certain point in space.
TEMPORAL DIMENSION

### 1. Is time a meaningful element of my game? Does the passage of time change anything in the game world even if the player does nothing, or does the world simply sit still and wait for the player to do something?
Time changes when the player progresses through the story by completing the level. However during the levels time will play no effect. There might be time based puzzles (like oxygen running out) but these do not affect the story progress time.

### 2. If time does change the world, what effects does it have? Does food decay, and do light bulbs burn out?
There might be time based puzzles that the player need to solve before he can progress through the levels but these do not affect the world he is in.

### 3. How does time affect the player’s avatar? Does he get hungry or tired?
In game time will not affect the player. Story-wise (completing levels) might affect the avatar.

### 4. What is the actual purpose of including time in my game? Is it only a part of the atmosphere, or is it an essential part of the gameplay?
Time is used to add more pressure during the gameplay. To give the player more of an illusion that the ship is breaking down.

### 5. Is there a time scale for my game? Do I need to have measurable quantities of time, such as hours, days, and years, or can I just let time go by without bothering to measure it? Does the player need a clock to keep track of time?
While the time only really progresses when the story continues. It is irrelevant to measure it. 

### 6. Are there periods of time that I’m going to skip or do without? Is this going to be visible to the player, or will it happen seamlessly?
There will be cutscenes showing the player how the world around him is progressing through time.

### 7. Do I need to implement day and night? If I do, what will make night different from day? Will it merely look different, or will it have other effects as well? What about seasons?
The spacecraft is in space so there will be no seasons nor day and night cycles; 

### 8. Will any of the time in my game need to be anomalous? If so, why? Will that bother the player? Do I need to explain it away, and if so, how?
During the active parts of the game, time will play no role in wether how many hours have passed. The end of level will simply skip set amount of hours if that is desired. Proper cutscenes should inform the player time has passed.

### 9. Should the player be allowed to adjust time in any way? Why, how, and when?
No, because time is not a major factor in this game; It is simply a means to tell the player that he is progressing through the game.

## ENVIRONMENTAL DIMENSION

### 1. Is my game world set in a particular historical period or geographic location? When and where? Is it an alternate reality, and if so, what makes it different from ours?
The game is set in a far distant future where mankind is exploring the wide universe with spacecrafts. 

### 2. Are there any people in my game world? What are they like? Do they have a complex, highly organized society or a simple, tribal one? How do they govern themselves? How is this social structure reflected in their physical surroundings? Are there different classes of people, guilds, or specialized occupations? CHAPTER 4
There is a political hierarchy were people are ranked from high to low. The high ranked people think of themselves as the better kind. Religion still plays a role in our society but is not as strong as it was before.

### 3. What do my people value? Trade, martial prowess, imperialism, peace? What kinds of lives do they lead in pursuit of these ends? Are they hunters, nomadic, agrarian, industrialized, even postindustrial? How does this affect their buildings and clothing?
Current value is imperialism. The people are colonizing planets and creating industrie. Most people during work hours are wearing uniforms reflecting their profession.

### 4. Are my people superstitious or religious? Do they have institutions or religious practices that will be visible in the game? Are there religious buildings? Do the people carry charms or display spiritual emblems?
Religion still exist in this world but there are no more religious buildings. Some people keep a charm with them.

### 5. What are my people’s aesthetics like? Are they flamboyant or reserved, chaotic or orderly, bright or subtle? What colors do they like? Do they prefer straight lines or curves?
Wearing a standard uniform has become a norm (not a must) for most people. Some people deviate from it by changing their hair color or adding accessories to their uniform. 

### 6. If there aren’t any people in the game, what are there instead, and what do they look like and how do they behave?
There are still people around in the spaceship but many of them have died because of what is happening during the game.

### 7. Does my game take place indoors or outdoors, or both? If indoors, what are the furnishings and interior decor like? If outdoors, what is the geography and architecture like?
The game takes place inside and outside the spaceship. Outside you will see the exterior of the spacecraft and distant planets/stars. There will also be a lot debris of the spacecraft. Inside of the ship will have a futuristic look and you will also see a lot of mechanical devices.

### 8. What are the style and mood of my game? How am I going to create them with art, sound, and music?
2D with a mix between cartoon and realistic style of sprites. The game is mostly calm as the player slowly progresses through the levels solving puzzles. The music needs to be of a calm nature that also gives a future/space vibe. Sound effects differ in volume depending if the player is outside or inside the spacecraft.

### 9. How much detail can I afford in my game? Will it be rich and varied or sparse and uncluttered? How does this affect the way the game is played?
The tiles and objects within the game need to fairly detailed. There needs to be good distinction between all the dynamic objects in the game. The use of a particle system is import here because we can use it to tell the player what is happening with the objects. An example is creating particles that are being drawn towards the gravity orbs.

## EMOTIONAL DIMENSION

### 1.Does my game have a significant emotional dimension? What emotions will my game world include? 
The player should feel an urge to survive. In the game world a certain amount of suspense and fear should be created.

### 2. How does emotion serve the entertainment value of my game? Is it a key element of the plot? Does it motivate characters in the game or the player himself?
The emotion in this game should motivate the player to continue playing the game unit it is finished.

### 3. What emotions will I try to inspire in the player? How will I do this? What will be at stake?
The main purpose of this game is to create a challenging game for the player. There is no hidden message nor is anything at stake. The player can redo the levels as many times as he needs to.
ETHICAL DIMENSION

### 1. What constitutes right and wrong in my game? What player actions do I reward and what do I punish?
The player needs to solve the puzzles in order to continue progressing through the game. The final destination for the player is looking way to escape from the spacecraft that has been damaged beyond repair. Wrongs would be trying to escape the boundaries that have been set by the designer and avoiding the puzzles. There is no real way to punish them but they will miss the challenge that this game could bring to them.

### 2. How will I explain the ethical dimensions of the world to the player? What tells him how to behave and what is expected of him?
Breaking the game is pretty self explanatory. The game has boundaries like, walls and killzones, that hopefully tells the player they need to solve the puzzle in order to progress.

### 3. If my game world includes conflict or competition, is it represented as violence or as something else (racing to a finish, winning an economic competition, outmaneuvering the other side)?
The game world does not contain conflict nor competition.

### 4. What range of choices am I offering my player? Are there both violent and nonviolent ways to accomplish something? Is the player rewarded in any way for minimizing casualties, or is he punished for ignoring them?
There can be more than one solution for each puzzle in the game, but they all are nonviolent and result in the same way.

### 5. In many games, the end—winning the game—justifies any means that the game allows. Do I want to define the victory conditions in such a way that not all means are acceptable?
No, there is only one way to finish the game and there won’t be any external factors that could change that outcome.

### 6. Are any other ethical questions present in my game world? Can my player lie, cheat, steal, break promises, or double-cross anyone? Can she abuse, torture, or enslave anyone? Are there positive or negative consequences for these actions?
There aren’t any other ethical questions in this game.

### 7. Does my world contain any ethical ambiguities or moral dilemmas? How does making one choice over another affect the player, the plot, and the gameplay?
There are non in this game.

### 8. How realistic is my portrayal of violence? Does the realism appropriately serve the entertainment value of the game?
The damage of the asteroid needs to be reflected back in the levels that the player plays. Broken machinery, gravity not working in certain rooms in the level, background sprites showing debris of the ship or dead people floating around. 
