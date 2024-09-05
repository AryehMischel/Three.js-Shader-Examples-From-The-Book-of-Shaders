# The opening Section of the book includes four Chapters:
<br />- [What is a shader?](https://thebookofshaders.com/01/)
<br />- [“Hello world!”](https://thebookofshaders.com/02/)
<br />- [Uniforms](https://thebookofshaders.com/03/)
<br />- [Running your shader](https://thebookofshaders.com/04/)

The chapers "What is a shader" & "Running your shader" both had no example work, so they are not including. 


**Chapter 1 Key Takeaways:**
<br />- GLSL Shaders end with the default output reserved global variable gl_FragColor. <br />- We can use Macros to do precompilation steps (define global variables or do some logic operations etc).<br />- We can determine the precision of our shaders by specifying the precision of our floats


**Chapter 2 Key Takeaways:** 
<br />- GPU Threads are blind to each other and have no memory of previous operations.
<br />- We send read only "Uniform" inputs from the cpu to the gpu threads to use as variables in our shader.
<br />- Typically, Uniforms are formatted as u_uniformName or iUniformName.