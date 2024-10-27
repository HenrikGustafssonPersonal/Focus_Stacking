# Focus_Stacking
This is a group project created in 2023. This project uses the in-focus parts of a set of images to combine them into a full focus images. 
This is done using a sobel filter and using the filtered images as masks to create the stack. Images were rendered in blender using different focal lengths and a groud truth without any depth of field was used to evaluate the generated focus stack.
Outputs were evaluated using Mean squared error, structural similarity index measure and Signal-to-noise-ratio.
