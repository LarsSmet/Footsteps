# Introduction
You're a wizard, stuck in a prison full of guards, you have to escape without being seen. But the guards won't make it easy for you, as they all watch different angles and patrol through the building.

This was an assignment for the course Game Design 1 at DAE. We got 2 keywords that we had to brainstorm around. It was also the first time that I worked in Unreal and the first time that I had to create my own game idea from scratch. I had a lot of fun and this definitely motivated me to get more into game design. 

[Gameplay video](https://www.youtube.com/embed/7Ic58PV7AJ4?si=bqexPUTc56HjoNwd) of the demo level.

# Goal
It was my goal to combine the stealth and puzzle genre to create a unique game experience that would spark the player their creativity. I wanted to make a game that could have multiple levels with multiple solutions.

# Gameplay and mechanics
The abilities allow you to solve the level in multiple ways. You have limited usages of each ability, so you need to make sure that you don't waste any!
# Enemies
The enemies have a vision cone that you have to dodge. Once you get seen by one, you die and go back to your previous checkpoint. Some of the enemies move, while others are stationary.
## Teleport
Your first ability is the teleport ability. It is a projectile that you shoot and once it reaches the end of its lifetime, the player gets teleported to that position. If it hits a wall, the teleport gets cancelled. The enemies can't see this ability, so it is the perfect way to dodge the enemies, by teleporting to the other side of their vision cone. 

![Teleport](https://github.com/LarsSmet/Footsteps/assets/97398099/d6025493-2b69-44db-b70b-4b0b3e1f8fef)

## Footsteps
The footsteps ability is your second ability. If it hits an enemy vision cone, the enemy will start to follow the footsteps. The footsteps continue infinitely, they only get destroyed once they hit something. When the footsteps are destroyed, the enemies that followed them will now start to patrol between that point and the enemy start point. If they were already patrolling, the point gets added to the patrol path of the enemy. The player can redirect this ability to the left or to the right once. 


![footsteps](https://github.com/LarsSmet/Footsteps/assets/97398099/c3d4bbb0-78c7-458a-84fd-c517e948f7cb)

# Evolution
Playtesting and listening to feedback was a fairly important part of the course. We had to make an evolution video, which you can find here:
[Evolution video](https://www.youtube.com/embed/IpugHuEYoWE?si=XTMpmQf6EToPdGKD)
# Improvements and what's next
I don't think I'll revisit this project any time soon. But if I had to remake it today, there are definitely some things that I would change. The first thing that I would change is the teleport, in the game you can't see the range. While the fixed range is definitely a part of the puzzle, it is pretty annoying that the player can't see how far the teleport would go. Currently, they have to remember the range and hope they calculated the distance correctly. So I would add a visual that shows the range, to make it a lot more player-friendly.

Another big part that I would change is the level design. It isn't super great and I didn't put a lot of thought behind it at the time, whilst it is actually super important for the game. The final thing that I would redo are the controls, they are pretty wonky right now. So I would make them a lot more user-friendly and intuitive. But mistakes are bound to happen in early projects, the most important part is that I learned a lot from it.


