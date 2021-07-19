# Weapon-Detection-Using-OpenCV
   Weapon Detection Using OpenCV
ABHINAV REDDY CHERLAKOLA
(abhinavreddy.cherlakola_2022@woxsen.edu.in)




ABSTRACT
Security is always a main concern in every domain, due to a rise in crime rate in a crowded event or suspicious lonely areas. Abnormal detection and monitoring have major applications of computer vision to tackle various problems. Due to the growing demand for the protection of safety, security, and personal properties, the needs and deployment of video surveillance systems can recognize and interpret the scene, and anomaly events play a vital role in intelligence monitoring. This paper implements an automatic gun (or) weapon detection using open cv.
INTRODUCTION 
Weapon or Anamoly detection is the identification of irregular, unexpected, unpredictable, unusual events or items, which is not considered as a normally occurring event or a regular item in a pattern or items present in a dataset and thus different from existing patterns. An anomaly is a pattern that occurs differently from a set of standard patterns. Therefore, anomalies depend on the phenomenon of interest [1] [2]. Object detection uses feature extraction and learning algorithms or models to recognize instances of various categories of objects [3]. Proposed implementation focuses on accurate gun detection and classification. The flow of object detection and tracking is shown in figure 1. Dataset is created, trained, and fed to an object detection algorithm. 

                                                               
                                                         
Fig.1. Detection and Tracking






Related Work 
We learned object detection by using open cv by reading “New object detection features in the OpenCV library” written by Druzhkov.[4] In this paper, images were given and the algorithm would identify the object with an accuracy of 97%, and we learned real-time object detection by reading “Real-Time Object Detection and Tracking Using Deep Learning and OpenCV”[5] in this we learned how to detect objects using CCTV.
Dataset
Image Dataset: We took a data file of 255 pictures of different types of guns and converted them into a Haarcascade file of Guns some of the images of guns are shown below.
Sample Gun Images:
Fig.2: Sample Pistol.                                            
 

Fig. 3: Sample Assault Rifle.



.
Fig.4: Sample Snipper

Methodology
Step 1 
Creating dataset  and Training 
We took a data file of 255 pictures of different types of guns and converted it into a Haarcascade file of Guns and trained the algorithm
Step2
 We tried accessing our webcam for accurate results. It tries to match the images in the given dataset, and if it matches the real-time video, it tells us whether gun/guns were detected.

Results
Based on the experiment, we used a gun picture on the mobile and got the following results. 
We showed a Snipper on our phone. The output is as below. 
 
Fig. 5: Snipper Image.
We showed a pistol image on our phone. The output is as below
 
Fig. 6: Pistol Image.
We showed a woman aiming with a pistol, the output is as follows.
                                       
Fig.7 Woman aiming with Pistol.

In  Fig.7, the weapon is detected and another blue highlighter is visible as it is detecting  more weapons if the woman has any.


References 
1.	Ruben J Franklin et.al., “Anomaly Detection in Videos for Video Surveillance Applications Using Neural Networks,” International Conference on Inventive Systems and Control,2020.
2.	H R Rohit et.al., “A Review of Artificial Intelligence Methods for Data Science and Data Analytics: Applications and Research Challenges,”2018 2nd International Conference on I-SMAC (IoT in Social, Mobile, Analytics and Cloud), 2018.
3.	Pallavi Raj et. al.,“Simulation and Performance Analysis of Feature Extraction and Matching Algorithms for Image Processing Applications” IEEE International Conference on Intelligent Sustainable Systems,2019.
4.	Druzhkov, P.N., Erukhimov, V.L., Zolotykh, N.Y. et al. New object detection features in the OpenCV library. Pattern Recognit. Image Anal. 21, 384 (2011). https://doi.org/10.1134/S1054661811020271
5.	G. Chandan, A. Jain, H. Jain and Mohana, "Real Time Object Detection and Tracking Using Deep Learning and OpenCV," 2018 International Conference on Inventive Research in Computing Applications (ICIRCA), Coimbatore, 2018, pp. 1305-1308, doi: 10.1109/ICIRCA.2018.8597266.




