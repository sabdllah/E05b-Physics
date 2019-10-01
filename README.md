# E05b-Physics
Exploring 2D physics and collisions.

In *main1.py*, you will need to apply gravity to the balls on the screen. To do so, you will need to find an appropriate gravity constant and assign GRAVITY to that number (line 17). Because of the way the Y axis works in Python Arcade, GRAVITY will need to be a negative number for the balls to fall.

You will then need to accelerate the balls according to the GRAVITY constant. You can call b.accelerate(x,y) on line 67. In the case of applying gravity, x will be 0 and y will be GRAVITY. 
I made gravity -0.9. This part was easy to understand and complete. 

*main2.py*, is a little more complicated. You will need to apply all the lessons you learned in main1.py, but now we want the balls to bounce off the walls. First apply the GRAVITY constant from main1.py and accelerate the balls. Then, lines 39, 45, 51, and 57 will ask you to bounce (reverse the velocity) of the ball when it hits a wall. Think about what we discussed in class. I am applying some friction so they don't bounce forever. *I added a margin to the wall to handle fast-moving balls. SCREENWIDTH - MARGIN would represent the right side of the window, for example.*
I edited the said lines and it appears that the balls move/ bounce of the others, however, the screen immediately disappears. I don't know what i've done wrong. 

*main3.py* is an opportunity for you to implement elastic collisions using the conservation of momentum. Assuming the animals are the same mass, they will just trade velocities. Insert your collision code at line 53. *For extra credit,* give each animal a random mass and use that to calculate the new velocities (remember that m1v1 = m2v2).
I added code to line 53 and it seems the animals collide, however, I'm not sure why the screen disappears quickly. It seems I have some problem with my code although I am unsure what it is.
