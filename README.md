# Rolling-and-bouncing-Ball-
Computer Graphics in OpenGL

ball.c file contains the code for bouncing and rolling ball.
circle.c file simply creates a circle with 4 sectors each with a different color. 
In order to compile the above files you need to type     
        cc ball.c -lGL -lGLU -lglut      
Graphics Transformations are done in C and not using the OpenGL api's. 
The physics concept of smooth rolling ( v=r*ω ) has been implemented during rolling animation.
The concept of projectile (parabolic path) motion has been implemented during the bouncing animation
