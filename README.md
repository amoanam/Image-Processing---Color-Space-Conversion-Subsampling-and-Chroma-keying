# Image-Processing---Color-Space-Conversion-Subsampling-and-Chroma-keying
This is a practical task sheet which will be about color conversion, chroma keying, Subsampling and Noise of images.

# Objective of the Task 

Transmission standards use different color spaces, due to the different end devices, however, cameras also use different color spaces to record videos, it is thus required to convert from one color space to a different one. We will tackle in this task sheet several parts of color space conversion and subsampling.

Afterward, we will have a look at traditional chroma-keying, a technique used in e.g. television studios. The key idea of chroma keying is to replace the background with something else, e.g. a weather map or similar.

Finally, we will check out how to reduce salt and pepper noise removal and edge detection for an image.


# Subtask 1: Color space conversion
The most commonly used color space for video processing is  𝑌𝐶𝑏𝐶𝑟, in the following cells we will manually implement such a conversion from digital RGB values

# Subtask 2: 4:2:0 chroma subsampling
After we are now able to convert RGB images to  𝑌𝐶𝑏𝐶𝑟, we can now implement chroma subsampling. The general idea here is that human perception is more sensitive to changes in luma than in color. We will handly 4:2:0 subsampling in this task

# Subtask 3: Chroma Keying
The idea is to use a setup consisting of a camera (where parameters like FOV/focal length, camera position are captured), a blue/green box, lights, and some animated/replacement for the background. Using such a recorded scene will end up, e.g., the following example image, background, and combined version

# Subtask 4: Salt and pepper noise
some white or black pixels occur randomly in an image, removing them will help to improve the image quality, and also for later post-processing the noise is usually not required. They usually originate from dead pixels inside the camera, thus they can also occur in all three channels (colored salt and pepper noise).
