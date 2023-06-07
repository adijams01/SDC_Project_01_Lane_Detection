# SDC Projects
## Table of contents
* [Prerequisites](https://github.com/adijams01/SDC_Projects#prerequisites)
1. [Lane Detection](https://github.com/adijams01/SDC_Projects#project-1-lane-detection-using-opencv)
2. [Traffic Sign Detection](https://github.com/adijams01/SDC_Projects#project-2-traffic-sign-classification)

## Prerequisites
Python 3.x

NumPy

Matplotlib

Tensorflow

opencv

Jupyter Notebook (optional:skip below steps and run it in collab)

Jupyter-Lab(For some projects it is better to run on lab than collab)

You can install all the required Python packages by running the following command:

Copy code
```
pip install opencv-python
```
Usage
Clone the repository:
bash
Copy code
```
https://github.com/adijams01/SDC_Projects.git
```

## Project 1: Lane detection using opencv

open this [notebook](https://github.com/adijams01/SDC_Projects/blob/main/SDC_Project_01_Lane_Detection/Lane_Detection.ipynb) and start running the cells

### Results

<img width="581" alt="Screenshot 2023-03-07 195334" src="https://user-images.githubusercontent.com/92617405/223450333-8760514f-2c9c-48a8-b552-1e2e690f5206.png">

### Refrences
* https://medium.com/@yogeshojha/self-driving-cars-beginners-guide-to-computer-vision-finding-simple-lane-lines-using-python-a4977015e232
* https://www.youtube.com/watch?v=Ly92UcnoEMY 
* https://www.youtube.com/watch?v=VOC3huqHrss
* https://www.youtube.com/watch?v=0rc4RqYLtEU&t=1s 
* https://automaticaddison.com/the-ultimate-guide-to-real-time-lane-detection-using-opencv/
* https://www.youtube.com/watch?v=eLTLtUVuuy4
* https://www.linkedin.com/pulse/chapter-1-finding-lane-lines-roadudacity-project-mouhcinesnoussi/?trackingId=%2Fgx%2BIwfATgSCf0h22od%2B7g%3D%3

## Project 2: Traffic Sign Classification

open this [notebook](https://github.com/adijams01/SDC_Projects/blob/main/TrafficSignClassification.ipynb) and start running the cells

### Results


<img width="350" alt="Screenshot 2023-04-14 194810" src="https://user-images.githubusercontent.com/92617405/232070485-43d59230-7c59-4c90-b872-45680d13962b.png">

### Classes

            'Speed limit (20km/h)',
            'Speed limit (30km/h)', 
            'Speed limit (50km/h)', 
            'Speed limit (60km/h)', 
            'Speed limit (70km/h)', 
            'Speed limit (80km/h)', 
            'End of speed limit (80km/h)', 
            'Speed limit (100km/h)', 
            'Speed limit (120km/h)', 
            'No passing', 
            'No passing veh over 3.5 tons', 
            'Right-of-way at intersection', 
            'Priority road', 
            'Yield', 
            'Stop', 
            'No vehicles', 
            'Veh > 3.5 tons prohibited', 
            'No entry', 
            'General caution', 
            'Dangerous curve left', 
            'Dangerous curve right', 
            'Double curve', 
            'Bumpy road', 
            'Slippery road', 
            'Road narrows on the right', 
            'Road work', 
            'Traffic signals', 
            'Pedestrians', 
            'Children crossing', 
            'Bicycles crossing', 
            'Beware of ice/snow',
            'Wild animals crossing', 
            'End speed + passing limits', 
            'Turn right ahead', 
            'Turn left ahead', 
            'Ahead only', 
            'Go straight or right', 
            'Go straight or left', 
            'Keep right', 
            'Keep left', 
            'Roundabout mandatory', 
            'End of no passing', 
            'End no passing veh > 3.5 tons' 

### Refrences
* [Data](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign?resource=download)
