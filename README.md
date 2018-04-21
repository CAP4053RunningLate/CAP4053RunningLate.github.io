# **Running Late DevLog**

**Player Movement**

Once the player character art and animations were complete, I began to work on allowing the player to be able to move the character across a basic level layout.  After watching several YouTube tutorials, I ran through several iterations on how to allow the player to move left/right and jump, with the final one being that if the player presses the A/D keys it allows for left/right movement, and if the spacebar is pressed it allows for jumping.  
//
// photo or video
//
With the ability to control player movement finally completed, now I had to refine it. While the player can move around and jump, it just looks unnatural because he just slides across the world since there is no animations to him, and because he doesn’t turn around when moving back, he just slides back while looking forward.
//
// photo or video 
//
My solution to the gliding issue, was to set the player running animations to be active whenever the player presses the A/D keys, that way the player looks like he is running across the world instead of gliding on it. I also implemented a switch onto the player that keeps track if he is facing right or not, that way I know if he is not facing right, to flip the character art to the opposite direction, making the player look more natural now when moving. 
//
// photo or video
//

