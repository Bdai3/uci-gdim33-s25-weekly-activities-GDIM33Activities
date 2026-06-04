# GDIM 33 In-Class Activities
## W1
### Activity 1
[Moodboard](https://docs.google.com/drawings/d/17QHlBYCw-vrBbK6CsiloAapOt14Z0ULUOkj95v_M29Q/edit?usp=sharing)

1. Most of them feature attacking enemies and receiving some kind of currency. Most of them are first person shooters, are set in an abandoned place, and are round based.
2. Audrey also likes many different type of games similar to me, and we both liked Genshin! We both draw stylized characters and enjoy looking at beautiful environments. 
3. Michael my LA and I have different tastes in games now, but we both grew up playing Call of Duty zombies! 


### Activity 2

![BreakDown](https://github.com/user-attachments/assets/ec194a32-123a-4e73-a5bd-2de8e1638c4d)


## W2
N/A

## W3
### Activity 1
<img width="1996" height="1214" alt="image" src="https://github.com/user-attachments/assets/0cf1918f-402c-4e2d-9766-dce1fcc71be8" />


### Activity 2

1. So that its eaasier to reference and remember that the scene variable exists.
2. The debug on the transtion nodes helpped me see that the transistion went through.
3. No, because my game uses the cursor to aim in the game. At no point will you not need your cursor.
4. Yes, players and enemies will have an alive state and dead state and the transition will happen when health drops to 0.


## W4
### Activity 1 

1. In my current itch build: players can move, aim with mouse, shoot with mouse one, hit and kill zombies, zombies chase the player, and players can spend points they've earned.
3. I want to know if the current machanics feel good to play curreently. If theres anything to add.
4. I will be play testing: Lawrence Le and Audrey Hu's game.

Notes 
1. This is cute
2. player feedback when shooting
3. delete open fence (players get confused)
4. movement speed is fine
5. UI pop up on door

### Activity 2
1. Yes because they just need to write it in inspector.
2. You can only have 4 in our activity, but you can have as many as you want normally.
3. Regenerate nodes allows you get nodes that you create. 

EXTRA CREDIT
<img width="1449" height="804" alt="image" src="https://github.com/user-attachments/assets/4491eb0b-8c92-4ee6-971a-6056d50a5c7c" />

## W5
### Activity 1
1. Create a new statue object that runs a method on the player
    1. Add object sprite into the scene
    2. Add 2D collider on the object 
    3. Create visual script that gets the players current position and check it’s distance from the statue
    4. Set up script to check if player is within the buy range of the statue
2. Player interacts with the statue to increase stats 
    1. If the player is within the range and Press E the method of boosting the players health will run
    2. Players need to have $2500 in order to purchase
    3. Script will get the player object's health variable and set it to 5. 
    4. Add hearts to the UI where 2 are hidden but then revealed if player has this upgrade

### Activity 2
1. I added a perk/upgrade that perminatly increases the players health when bought. I was also trying to fix my Nav Mesh.

## W6
### Activity 1
1. Goal: Testing if the round system is functioning as intended.
    1. Can't tell when out of ammo
    2. Dpn't have round count UI
    3. Lower buy range for perk
    4. Feedback on gun
    5. Wish they had mouse
    6. Good Game!
    7. Add player taking damage frame
   
### Activity 2
1. Multiply makes it darker because it when you multiply it, the RGB values decrease.
2. It'll become more translucent since we're multiplying by values less than one which will cause the values to decrease.
3. The vertices on the mesh holds the data that maps the data on to the UV map. 
4. Yes, its really interesting as an artist! 

## W7
### Activity 1
1. Vertex color is stored as data in each vertex of the mesh.
2. Everything between the vertices are blended together and filled by the corner colors.
3. Artists can use it to check their mesh to make sure they're accurate. Vertex coloring is useful for debugging your meshes.
4. The green patch on his backside looks off. 
5. Using UV data to check polygon optimization.
6. The lighting by default is flipped which means the lighting appears on the wrong side.
7. Instead of multplying the values of the background we add it to make it more transparent than darker, if we multiply it the valuees of RGB is 0-1 which will decrease the value which will make it darker.   

## W8
### Activity 1
1. Something I added since milstone 2 was the gun has a muzzle flash when the player shoots the gun.
2. [Itch Build](https://senseiwuhooo.itch.io/dead-calling-milstone-3)
3. My goal for this playtest is to see anything that I should add and things work.

Notes
1. Round color to bright
2. Fix buying perk after taking damage
3. Shocked spent money on ammo
4. Cost pop up ui
5. Running into wall its a bit jittery
6. Gun Dsync when you walk into the wall (use transfform position intead of rigid body)
7. Bullet size bit to small or color is hard to see
8. Enemies dont collide with perk but player does 
9. Fench cant go through
10. VFX stays sometimes after firing
11. Add hit indication on enemies

### Activity 2B Questions
1. Time increaases forevery but since the fraction node only turns the decimals into fractions, it hits 0 and resets. This is why it creates a blink effect.
2. We want to make the default black so that when we render the shine which is white we can see it. In unity white is desfault and if we did white on white it wouldn't read well.
3. Its reading as a material and not a sprite renderer which is why it doesn't show on anything else. Also it's only on one object.
4. We multiply into the fraction because we want the animation to play at a certain interval and by multiplying the time by 1 it keeps it consistant.

## W9
### Activity 1
1. My team went over, Subnautica.
2. One feature we wanna focus on is the color of the water.
   - We believe its a postprocessing effect that covers the full screen.
   - It adds a color filter over the postprocessing effect when the player enters a new area.
   - This effect is triggered based off player position (depth which effects ) and biome type. 
3. Exit water transition effect.
   - This is also a full screen effect.
   - It uses an animated texture to play an animation when the player passes through the water.
   - This texture plays when the player passes the line of water and land (indicating the player is moving out of the water). 

### Activity 2
<img width="2456" height="1507" alt="image" src="https://github.com/user-attachments/assets/6ccc2a0d-7807-4ace-b9b1-100592a868fb" />
1. I fixed up my ammo shine graph. Before this graph use to run but only start half way and end the shine effect at the bottom left. The issue was that the texture I put for the shine effect was set to clamp rather than repeat which causes the effect to end early and start betweeen 0-1. After fixing that the animation was to small for my sprite so I had to multiply the UV to cover my whole ammo crate sprite.

## W10
### Activity 1
1. Since milestone 3, I've added audio (BGM, Zombie damage sounds, reload sound, and zombie death sounds) and multiple spawn points/locations for the zombie.
2. https://senseiwuhooo.itch.io/dead-calling-final-submission
3. My Goals is to find any game breaking bugs and to see if theres anything to add given the remmaining time.

Notes
1. Kill enemy instantly instead 
2. Limit Fire Rate

### Activity 2
1. First we would identify the game's mechanics/loop and focus on CORE mechanics needed
2. Then Identify the different primary systems that can actualize the mechanics and effect the game play
3. Identify what sort of variables / components can be used to support the mechanical function and systems
4. Next visualize/note them for retention and development references using a break down chart 
5. identify how these variables / components will be communicated between systems through connecting the different parts within the breakdown chart
6. Planning well, will impact how much you can get done within a project. A well planned project will allow you to complete more with less difficulty, compared to poor planning which can make mechanics to sound easier than they are to implement. Also planning well will help developers see generally the workload and different interactions that will happen within your game. From viewing this, we can see the scope of the game and can cut content depending on the time available.
7. After planning, before implementation, breaking down each tasks using a "task break down" will prove helpful and speed up the process. This is because you're making a course of action where you head into engine knowing generally what to do and don't waste time on what to do since you thought through it once.
