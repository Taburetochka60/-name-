# Layers
# Dence
Dence (fully connected layer) - N parameters conectet to M parameters

![](Pastedimage20240614210039.png)
# Convolutional

A neuron (core) is a filter, that is, a matrix of certain coefficients (weights). Their optimal value is established during the training of the neural network.

 The neuron multiplies the values of the filter matrix by pixel values. The result of the multiplication is summed. The resulting number shows the filter location in the picture. This process is called a package. For example, in a 32x32 picture, there are 784 squares that a filter can allocate. These numbers create a 28x28 matrix.
 ![](Pastedimage20240614210106.png)
![](a5fc3d078f98465601ac65f5be909300.gif)
# max/average pooling

There are two types of pooling: maximum and average. The first returns the maximum value from the kernel-covered portion of the image. And the average pool returns the average of all the values ​​of the part covered by the kernel.

![](Pastedimage20240614220445.png)

# Soure

Как работает сверточная нейронная сеть - https://robotdreams.cc/blog/209-kak-rabotaet-svertochnaya-neyronnaya-set#:~:text=Сверточные%20нейросети%20—%20это%20модель%20глубокого,для%20поиска%20границ%20в%20изображениях

Наглядно о том, как работает свёрточная нейронная сеть - https://habr.com/ru/companies/skillfactory/articles/565232/
