Problem statement:
Traffic signals are crucial for regulating vehicle flow and ensuring road safety. 
However, manual monitoring of traffic lights is inefficient and prone to human error, 
especially in busy urban areas. Developing an automated system capable of detecting 
traffic lights in real time from images and video streams can significantly enhance 
traffic management and reduce accidents caused by signal violations. Traditional 
image processing methods face challenges in accurately detecting traffic light colors 
due to varying lighting conditions, occlusions, and different signal designs. This 
project aims to develop a robust computer vision-based system that can detect red, 
yellow, and green traffic lights using HSV color space segmentation. The system 
processes both still images and real-time video streams to identify the active traffic 
light and provide corresponding actions such as STOP, WAIT, or START.
Abstract:

Traffic light detection plays a vital role in modern intelligent transportation systems 

and autonomous driving technologies. The ability to accurately detect and interpret 

traffic lights in real time ensures smooth traffic flow and improves road safety. This 

project presents a computer vision-based approach for real-time detection of traffic 

lights from images and video streams. Using OpenCV and HSV color space 

segmentation, the system identifies red, yellow, and green traffic lights and provides 

corresponding driving actions such as STOP, WAIT, and START.

The methodology involves converting input images or video frames to the HSV color 

space, which is more effective for color segmentation under varying illumination 

conditions. Specific HSV ranges for red, yellow, and green colors are defined to 

create masks that isolate potential traffic light regions. Contours are extracted from 

these masks, and the system filters detected regions based on contour area to 

eliminate noise. Bounding boxes and labels are then drawn on the detected traffic 

lights to visually indicate their presence and the associated driving instruction.
Introduction:

Traffic lights are fundamental components of road infrastructure that control vehicle 

movement at intersections, pedestrian crossings, and other critical points. With 

increasing urbanization and vehicular traffic, ensuring that drivers comply with traffic 

signals is essential to prevent accidents and traffic congestion. Automated traffic light 

detection systems are becoming increasingly important to support traffic 

management and enable autonomous driving capabilities.
Conclusion:

This project demonstrated an effective and efficient method for real-time detection of 

traffic lights from both images and video using color segmentation in the HSV color 

space. The system successfully identified red, yellow, and green signals and provided

corresponding driving instructions, showcasing its potential for integration into 

intelligent transportation and autonomous driving applications. Despite its promising 

results, the system has limitations under poor lighting or complex backgrounds, 

indicating room for improvement. Future enhancements may include incorporating 

machine learning-based classifiers and temporal analysis for more reliable and 

accurate detection. Overall, this work contributes to the development of automated 

traffic signal recognition systems that can enhance road safety and traffic efficiency. 

Moreover, the simplicity and lightweight nature of the approach make it suitable for 

deployment on embedded systems or edge devices used in smart vehicles. By relying 

solely on color information and basic contour analysis, the system avoids the 

computational overhead of deep learning models while still maintaining acceptable 

accuracy. This makes it ideal for applications where resources are limited but real-

time performance is critical, such as in driver-assistance systems or traffic 

surveillance setups.
