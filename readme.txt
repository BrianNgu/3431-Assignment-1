The elements that I was able to implement sucessfully everything except for the bubbles. I added the ground box, I added two rocks. 
For the seaweed, I created 10 eclipses, animated it so it swayed back and forth, and positioned it to be on top of the big rock. 
For the fish, I added 2 eyes with pupils, 1 head, 1 body, 2 fins. It also swims in a circle around the seaweed.
I created a human character with no arms, which moves in the x and y directions, The legs kick and the feet do not move.
Where I struggled was creating the bubbles. I made a function that draws the bubbles which works only in the beginning of the code.
When first ran, 4 bubbles are generated which go upwards but it does not repeat every 4 seconds. The bubbles do osicilate, and I made the bubbles
appear as close to the mouth as I could. 

I implemented osicilation for the bubbles by adding this line to my drawBubbles function: // gRotate(2* (TIME % 360) * 100, 5, 5, 5);
This line makes it so the bubles that it creates rotates around the x, y, and z axis. 
The first argument 2* (TIME % 360) * 100 determines the angle of rotation