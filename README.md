# Mandlebrot-Set

The Mandelbrot set is a famous mathematical object defined by a very simple rule. Nevertheless the Mandelbrot set itself possesses interesting and complex properties which can be seen graphically. This is undoubtly related to the fact that it is a fractal object.

## Generating the set

Consider a fixed complex number c. Starting with z0=0 we can generate the sequence of numbers z0,z1,z2,z3,⋯ by following the rule
<br>
#### zn+1=zn^2+c
<br>
The c number belongs to the Mandelbrot set if and only if the zn sequence is bounded by lim abs(z)->2.0

## __________________________________________________________________________________________

Here's a python script to generate a Mandlebrot set image file with desired resolution and number of iterations to check the bounding criteria.

### The image is being generated in two steps :
<br>
1.) First, the upper half portion of the image is computed by setting each pixel to a desired value using the code.
<br>
2.) Next, the upper half portion generated is cropped and flipper to produce a mirror image of itself and is transposed on the original generated image in first step.
<br>

### Hence, a complete image of Mandlebrot set is generated, since the figure is symmetric in nature.

### RGB values can be altered to produce a variety of appearances for the same.
<br>
#Some sample outputs produced for various resolutions and number of iterations have been added to the 'Outputs' folder.
