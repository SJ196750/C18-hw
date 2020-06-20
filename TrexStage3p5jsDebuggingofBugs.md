# Trex Stage 3 p5.js - Debugging of Bugs
# Bounty of Bugs - PRO C-18


1. Bug-1
* Trex is not standing on the ground completely
* Debug - Setting the collider radius
*     Code change - trex.setCollider("rectangle",0,0,100,100);
 
2. Bug-2
* Trex is not seen after it collides with the obstacle i.e. the obstacle comes in front of it and hides it
* Debug - Setting the depth  for the obstaclesGroup
*     Code Change - obstacle.depth = trex.depth;
*                 - trex.depth;

 
 3. Bug-3
 * Trex is going beyond the length of the obstacle after colliding with it
 * Debug - Setting the collider radius for the obstacles
 *     Code change - obstaclesGroup.setColliderEach("circle",0,0,50);  

                                                              
      By Shonali Jash
      
