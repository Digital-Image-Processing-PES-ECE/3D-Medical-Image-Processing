# Project Name

### Project Description:
#### Summary - This project performs preprocessing tasks on 3D brain scans to enhance clarity for easy analysis. Morphological processes like dilation, erosion, opening and closing are performed for image enhancement. The main objective of this project is to compare and pick the best possible methods for image enhancement.

#### Course concepts used - 
1. Histogram Equalization
2. Gaussian filtering
3. Median filtering
4. Laplacian filtering
5. Sobel filtering
6. Morphological operations (Dilation, erosion, opening, closing)
   
#### Additional concepts used -
1. Otsu's threshold algorithm
   
#### Dataset - 
https://www.kaggle.com/datasets/shakilrana/brats-2023-adult-glioma

#### Novelty - 
1. Applying 2D filters on 3D image for enchancement and clarity 
2. Threshold masking to isolate just the organ (removing background)
   
### Contributors:
1. Sohni Rao (PES1UG22EC291)
2. Samhitha Shetty (PES1UG22EC256)

### Steps:
1. Clone Repository - https://github.com/sohnirao/3D-Medical-Image-Processing.git

2. Install Dependencies - Required python libraries: Numpy, Nibabel, Matplotlib, Skimage

3. Run the Code - On any python supported platform. 

### Outputs:
* Important intermediate steps
  Histogram equalization:
  ![image](https://github.com/user-attachments/assets/76be641b-07ff-4eda-b9e6-00fcedc1ae1e)
  Edge detection:
  ![image](https://github.com/user-attachments/assets/356e7479-3705-479e-9471-5c97266b75c4)

  
* Final output images
  ![image](https://github.com/user-attachments/assets/30a9260e-4ad8-4ae5-bcef-2c96b42f1312)


### References:
1. https://youtu.be/UIgaLDgb2fY?si=VWq_k6gcOHLDCK_Z
2. https://github.com/lukepolson/youtube_channel/blob/main/Python%20Tutorial%20Series/image_processing1.ipynb
3. https://scikit-image.org/docs/stable/api/skimage.filters.html
   
### Limitations and Future Work:
 The results indicate that with a different combination of filters, different outputs can be achieved based on requirements. Further trial is needed to determine optimal combination of process to enhance the image. 
