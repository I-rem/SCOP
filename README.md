# SCOP
Basic GPU rendering with OpenGL

**Summary:** This mini project is a first step towards the use of OpenGL.. And other
GPU rendering API.

Your goal is to create a small program that will show a 3D object conceived with a modelization program like Blender. The 3D object is stored in a `.obj` file. You will be at least
in charge of parsing to obtain the requested rendering.

In a window, your 3D object will be displayed in perspective (which means that what
is far must be smaller), rotate on itself around its main symmetrical axis (middle of the
object basically...). 

By using various colors, it must be possible to distinguish the various
sides. 

The object can be moved on three axis, in both directions.

Finally, a texture must be applicable simply on the object when we press a dedicated
key, and the same key allows us to go back to the different colors. A soft transition
between the two is requested.

The technical constraints are as follows:
- You’re free to use any langages (C / C++ / Rust preferred )
- You’re free to choose between OpenGL, Vulkan, Metal and the MinilibX
- Have a classic Makefile (everything you usually put in there).
- You can use external libraries (other than OpenGL, Vulkan or Metal) ONLY to
manage the windows and the events.

No libraries are allowed to load the 3D object, nor to make your matrixes or to load
the shaders.

It is crucial that you can present during defense at least the 42 logo given as resources, turning around its central axis
(careful, not around one of its corners), with some shades of gray on the sides and a
texture of _ponies_, _kitten_ or _unicorn_ your choice.

During the defense, naturally more 3D objects will be tested.

## Resources
https://learnopengl.com/Getting-started/OpenGL

https://www.opengl-tutorial.org/beginners-tutorials/

https://engineering.monstar-lab.com/en/post/2022/03/01/Introduction-To-GPUs-With-OpenGL/

https://timallanwheeler.com/blog/2024/01/01/rendering-with-opengl/
