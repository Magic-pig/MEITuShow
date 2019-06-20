# MEITuShow
HSI and Matrix   
First, three buttons are created in the UI interface. These three buttons process images by different mechanisms. PrimaryColor changes the hue, saturation, and brightness of the image by selecting the HSI value of the image pixels.
首先在主界面创建了3个按钮，这三个按钮分别是通过不同的机理来处理图像.PrimaryColor通过选取图像像素的HSI值来改变图像的色调，饱和度，亮度
ColorMatrix processes the image by multiplying the image and the matrix. As shown above, the initialization matrix is ​​processed as the original image. Two buttons are set. Change, Reset, Change In order to change the matrix, ReSET initializes the matrix.
ColorMatrix 通过图像与矩阵的乘积，处理图像，如上图，初始化矩阵处理后为原图，设置两个按钮，Change,Reset，Change为了改变矩阵，ReSET初始化矩阵。
The third button implements four images in a layout, the original image, the negative image (negative film = 255 - original image), the nostalgic effect, and the relief effect (the pixel value of the previous point - the pixel value of the latter point +127)
第三个按钮实现了一个布局中显示4幅图像，原图，Negative图（底片=255-原图），怀旧效果，以及浮雕效果（前一点的像素值-后一点的像素值+127）
