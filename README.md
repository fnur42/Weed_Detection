# Weed_Detection
I was the software captain of the KTUN ARMAS İKA team, which was a finalist in 2022 Teknofest. I worked alone in the team in image processing.
We pulled 15,000 weed datasets ourselves and labeled them all.
In real time, instant detection of the plant from the camera can be realized.
In the code I wrote, I installed the darknet and pulled the data from it.
There are obj.data, obj.names, process.py and training files on the drive.
With the process.py file, I determined what percentage should be drawn for the test and what percentage for the train. In this way, it was automatically pulled.
The obj.names file contains the tag name. In the obj.data file, the necessary paths are given.
As a result of the test, the accuracy value was around 90%.
In my project, the YoloV4-tiny model, which is the model that allows us to reach fast and efficient results, was used. Tenserflow, OpenCv and keras, which are deep learning libraries, were used.
