# Face-Emotions-Recognition
In this project i have created a custom trained model for emotion detection detection. To do so, I used the dataset available on Kaggle. Then converted this data into an array and then trained it on MobileNetV2 model using transfer learning technique and then saved this model tu use it in the detection part.

To apply my emotion detection, I also needed a face detection model. For that, I’ve used a pretrained face detector named res10_300x300_ssd_iter_140000 from OpenCV. 
This is the DNN for face detection. Then I applied a prediction function to our webcam using cv2. This function first applies a face detector to the video frame, 
detecting faces using it. After detecting faces, it applies our emotion detection model to those faces and gives us the results.



You can see some of the results as i have used very less data because i dont have a good machine the accuracy was not that good but if we train the model on entire available dataset the accuracy can be very very good.

![15 08 2022_18 03 57_REC](https://user-images.githubusercontent.com/93977986/184638984-a3132892-3968-48d9-8a2d-7d77ffbecb90.png)
![15 08 2022_18 03 24_REC](https://user-images.githubusercontent.com/93977986/184638988-2c5bd9e1-a7ce-4fd1-8f2f-2c4f3bc8c451.png)
![15 08 2022_18 03 06_REC](https://user-images.githubusercontent.com/93977986/184638994-33044b75-d32a-4689-99c5-96c122a87715.png)
![15 08 2022_18 02 40_REC](https://user-images.githubusercontent.com/93977986/184638998-1aea54f5-b5cb-4129-ae0d-cb9b2e43669d.png)
![15 08 2022_18 02 17_REC](https://user-images.githubusercontent.com/93977986/184639001-df4b44ed-b4a2-4687-9dcb-30a2d4deaea6.png)
