# Parking Spot Detector in real-time using Mask RCNNs

This is a mini project that aims to detect free parking spots using machine learning. This is not for usage in parking lots and just for normal parking spots along the road. 

## Guide
1. Install Anaconda or can use virtualenv as well. Can work without these too, but virtual environment is recommended.
2. Create new environment and install dependencies : ``` pip install -r requirements.txt ```
3. Install Mask-RCNN. Instruction can be found [here](https://github.com/matterport/Mask_RCNN)
4. Add test videos to test_images and modify the project.py file accordingly to open the required video.
5. Can also use live video feed by making changes in the project.py file.
6. Run the script by typing : ``` python project.py ```
7. A new window will pop-up with bounding boxes.

> Note that it is recommended to run this on a good GPU for more efficiency.
