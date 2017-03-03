# set-titan-dp

It's inspired by [Nvidia GPU Coolness](https://sites.google.com/site/akohlmey/random-hacks/nvidia-gpu-coolness)

The Processing power of GTX Titan 
is 4500 GFLOPS (Single) [1300-1500 GFLOPS (Double)](https://en.wikipedia.org/wiki/List_of_Nvidia_graphics_processing_units#GeForce_700_Series).
However the double precision power is not enabled by default.
When it's installed on a remote (headless) server, it's hard to enable it.

Now you just need to edit the file dp with first line 

	dir=[right dir]

and run ./dp 

everything is done!
