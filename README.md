<p align="center">
<img src="https://user-images.githubusercontent.com/51369142/111650757-843d0800-87fd-11eb-9b2a-b54e81b90b05.jpg" width="400" height="300">
 </p>
 
# Object Detection Carla
This repository aims to provide an object detection system in carla simulation environment. YOLOv3 algorithm is chosen as a detector system to detect and classify pedestriants, vehicles and objects on the road. This algorithm is based on [YOLOv3: An Incremental Improvement](https://pjreddie.com/media/files/papers/YOLOv3.pdf) which originaly implemented in [YOLOv3](https://github.com/pjreddie/darknet)

# Requirements
1. python 3.7
2. Opencv 3.4.2
3. numpy

# Installation
To start with the implementation
1) Download [CARLA simulator](https://carla.org/2020/12/22/release-0.9.11/) (version 0.9.11).

2) Clone the following repository
```
git clone https://github.com/shayantaherian/Object_Detection_Carla.git
```
3) Copy `Object_Detection.py` in `CARLA_0.9.11/PythonAPI/examples` folder.#

5) Run `CarlaU£4.exe` to connect with the server.

6) Finally run `Object_Detection.py`.

Note that to use yolov3 for this task, it is required to download yolo weights from [yolov3.weights](https://drive.google.com/file/d/1xYasjU52whXMLT5MtF7RCPQkV66993oR/view). Examples of this detection system in carla environment can be seen as follows:

<p align="center">
<img src="https://user-images.githubusercontent.com/51369142/111666708-e13fba80-880b-11eb-98e6-5aa09e7621c9.PNG" width="400" height="300"/>                                     <img src="https://user-images.githubusercontent.com/51369142/111666881-0d5b3b80-880c-11eb-91b0-e4de670b6988.PNG" width="400" height="300"/>
<img src="https://user-images.githubusercontent.com/51369142/111667461-a25e3480-880c-11eb-97e2-6d08b26e3a4a.PNG" width="400" height="300"/>
<img src="https://user-images.githubusercontent.com/51369142/111667575-c28df380-880c-11eb-8814-530555725801.PNG" width="400" height="300"/>
</p>
