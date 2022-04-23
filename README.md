# perlin.3d
3D perlin noise for Pure Data (pd) - control signal input/output

Install by adding the directory perlin.3d to one of pd's paths.
The abstraction perlin.3d expects the arguments:
* number of octaves
* persistance value
* "normalize" flag if you want to ensure that the sum of all octaves will never exceed 1

Explanations on Perlin noise (and also the tutorial that this abstraction is based on):
* https://rtouti.github.io/graphics/perlin-noise-algorithm
