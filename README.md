# DiffusionEq4PathPlanning
Quick and dirty explorations on the use of the [diffusion equation](https://en.wikipedia.org/wiki/Diffusion_equation) for 2D and 3D path planning.

![image](https://github.com/user-attachments/assets/ca1e4586-4b77-430e-a3aa-b74669084a96)


## Install [Taichi](https://github.com/taichi-dev/taichi)
`pip install --upgrade taichi`

## My first attempt, using only Numpy
* [First Attempt Path Planning Using diffusion - 2D and 3D - Pure Numpy.ipynb](./First%20Attempt%20Path%20Planning%20Using%20diffusion%20-%202D%20and%203D%20-%20Pure%20Numpy.ipynb)

![image](https://github.com/user-attachments/assets/167a4ae9-99e4-46be-b754-44bd40a390da)

![image](https://github.com/user-attachments/assets/76874e1c-16be-4019-b327-7f113e455538)



## Second attempt, using Taichi and Depth Images (Maps)
* [Second Attempt Path Planning Using diffusion - 3D - Taici.ipynb](./Second%20Attempt%20Path%20Planning%20Using%20diffusion%20-%203D%20-%20Taichi.ipynb)

![image](https://github.com/user-attachments/assets/4c89033f-1019-40ec-b979-26000cdc3bd6)

![image](https://github.com/user-attachments/assets/b5513f6b-bc75-4ae3-9626-ac0f39b389cc)

![animation](https://github.com/user-attachments/assets/64472383-660e-4a84-8183-bf950c5005c7)





## Future Improvements (aka "I hope someone else will do it")
* Make it faster
* Adjust the dimensions on the X,Y plane so the image is not distorted
* Improve the problem where the path leaks through gaps between points in many situations
* Clean the code, add more comments, etc.

### If you want to save animations to HTML, install [Kaleido](https://github.com/plotly/Kaleido)
`pip install kaleido`

