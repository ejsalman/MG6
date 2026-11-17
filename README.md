# MG6

1. If you put a for-loop in an Update method, the entire for-loop will run before the end of the current frame. So, if you have a long for-loop, it will cause the game to lag since it HAS to be done before the end of the frame; it won't happen over the course of multiple frames.
2. One of the issues with the programming logic is that the player's collisions are disabled until they touch the ground or a platform, meaning that the player could phase through the side or the top of the game's border. 