# DiffusionEq4PathPlanning
Quick and dirty explorations on the use of the [diffusion equation](https://en.wikipedia.org/wiki/Diffusion_equation) for 2D and 3D path planning.

## Install [Taichi](https://github.com/taichi-dev/taichi)
`pip install --upgrade taichi`

## My first attempt, using only Numpy
* [First Attempt Path Planning Using diffusion - 2D and 3D - Pure Numpy.ipynb](./First%20Attempt%20Path%20Planning%20Using%20diffusion%20-%202D%20and%203D%20-%20Pure%20Numpy.ipynb)

## Second attempt, using Taichi
* [Second Attempt Path Planning Using diffusion - 3D - Taichi.ipynb](./Second%20Attempt%20Path%20Planning%20Using%20diffusion%20-%203D%20-%20Taichi.ipynb)

## Future Improvements (aka "I hope someone else will do it")
* Make it faster
* Adjust the dimensions on the X,Y plane so the image is not distorted
* Improve the problem where the path leaks through gaps between points in many situations
* Clean the code, add more comments, etc.

### If you want to save animations to HTML, install [Kaleido](https://github.com/plotly/Kaleido)
`pip install kaleido`

