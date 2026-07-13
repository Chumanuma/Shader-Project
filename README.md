VIDEO LINK: https://drive.google.com/file/d/1nl7-kU_HKNywFpjreIdOst4qReX_FmQo/view?usp=sharing
GITHUB LINK: https://github.com/Chumanuma/Shader-Project

This just uses objects included with Unreal Engine. 

Simple Material creations with different settings to showcase.

From left to right

1. Default settings colored ball
2. Mirror reflection ball
3. A comic book style red ball
4. Metallic colored ball
5. Transformation ball

ParamVector nodes for changing the basecolor for each sphere, and a small time node setup for the transformation.

 Time > Sine > Multiply A > 
                                 >>>             Multiply A 
Constant Node > Multiply B >                                  >  World Position Offset
                                VertexNormalWS > Multiply B

The above is text form but the same set up is in the video.
