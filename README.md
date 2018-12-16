### How to run the code
Mainly run on `dcGan.py`, differentable render part is in `pyrender_testoptimum.py`. The rendered input images are in `bus` folder. <br>

`./bus` <br>
Folder contains rendered images. Each image has 3 different views generated randomly. <br>

`./dfRender` <br>
Source code for differentiable render layer. <br>

`./failure` <br>
Failure images which are learned without point shift. <br>

`./real_image_render` <br>
Source code to generate real images from shapeNet. <br>

`./dcGan.py` <br>
Main code to run. <br>

`./diff.py` <br>
Code to calculate point shift distance. This is used to debug and see the result numerically. <br>
