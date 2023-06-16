# PCA-Mini-Project---Face-Detection-or-Convert-an-image-into-gray-scale-image-using-CUD
Mini Project - Face Detection or Convert an image into gray scale image using CUDA GPU programming
## Aim :
To develop a face detection algorithm utilizing CUDA GPU programming. By leveraging the parallel computing power of GPUs, the goal is to accelerate the face detection process and achieve real-time performance.
# Procedure :
```
1. Load the input image and allocate memory on the GPU.
2. Copy the image data from the host (CPU) to the device (GPU) memory.
3.  Implement a CUDA kernel to convert the image into a grayscale image using parallel processing. Each thread will handle a pixel and apply the appropriate grayscale transformation.
4.  Implement a face detection algorithm, such as Viola-Jones or a deep learning-based approach, utilizing the GPU. This algorithm should analyze the grayscale image and identify the regions containing faces.
5. Transfer the resulting face detection data back from the GPU to the CPU memory.
6. Perform any necessary post-processing steps on the CPU, such as drawing bounding boxes around the detected faces.
7. Display the image with detected faces or save it to disk.
```
## Output :

### Input :
![image](https://github.com/vishnudorigundla/PCA---Mini-Project-Mini-Project---Face-Detection-or-Convert-an-image-into-gray-scale-image-using-CUD/assets/94175324/be25e864-5f25-45af-8b4c-21f12f786488)
### Output :
![image](https://github.com/vishnudorigundla/PCA---Mini-Project-Mini-Project---Face-Detection-or-Convert-an-image-into-gray-scale-image-using-CUD/assets/94175324/409dbd6f-3f6b-4572-b002-392b9cea2d46)


## Result :
The CUDA program successfully converts the input image to grayscale using the GPU. The resulting grayscale image is saved as an output file. This example demonstrates the power of GPU parallelism in accelerating image processing tasks.
