# linmath

Reimplementation of the [linmath](https://github.com/datenwolf/linmath.h) header only library for graphics programming math.

The motivation of linmath is to provide a more consistent and slightly more usable interface than the original implementation.

linmath reuses the existing interface of the original implementation meaning the header files can be easily switched out for existing projects with only none to a few corrections required. Similarly, as stated in the original implementation:

> The types are deliberately named like the types in GLSL. In fact they are meant to be used > for the client side computations and passing to same typed GLSL uniforms.

The mat4x4 type is stored and operated on in column major order.
