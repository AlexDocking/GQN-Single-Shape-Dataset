# GQN-Single-Shape-Dataset
Datasets for CS course

The three datasets I have created are as follows:

1. 'Shapes'
There is a single coloured object against a black background, and the light source is fixed. The data is in rar format because that was the default when I archived it, not because I thought this would be the most convenient. The installs at the top should have installed a package for opening rar files anyhow.

There are four parts to this dataset, with a total of 50,000 scenes with 12 images per scene. Images are 32x32

2. 'RGB Cube Triangle'
There is a red, green or blue cube or triangular prism, against a grey background. There is no light source. Again this is rar format.

There is only one part in this dataset, with 1000 scenes, with 16 images per scene. Images are 32x32

3. 'Multiple Shapes'
There is a grid of 3x3 on which there are red, green and blue cubes of a random number. The cubes may be either large or small. They are on a grey checkerboard floor with a grey background. There is a single light source. This is zip format because at this point I realised this would be more compatible for different operating systems.

There are twenty parts to this dataset, with a total of 10,000 scenes with 16 images per scene. Images are 64x64

Viewpoints
The position and orientation of each observation image are stored in a file for each scene called 'viewpoints.csv'. The format of the columns in the files are as follows

Index

x position

y position

z position

sin of the x Euler angle in radians

cos of the x Euler angle in radians

sin of the y Euler angle in radians

cos of the y Euler angle in radians

sin of the z Euler angle in radians

cos of the z Euler angle in radians

x value of quaternion

y value of quaternion

z value of quaternion

w value of quaternion
