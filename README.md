# COVID-19-Mask_detector
## Real Time Mask Detection
### STEPS
1. Clone this repository
2. Clone [AlexyAB's](https://github.com/AlexeyAB/darknet) darknet implementation
3. Follow AlexyAB's README to build the repo. Run the demo successfully
4. Copy this repo's `mask.py` and paste it into `./darknet/`
5. Copy this repo's `yolo-obj.cfg` and paste it into `./darknet/cfg/`
6. Copy this repo's `obj.data` and paste it into `./darknet/cfg`
7. Copy this repo's `obj.name` and paste it into `./darknet/data/`
8. You can find pre-trained weights [here](https://drive.google.com/drive/folders/14LGXxTuqg3bg6rIVvPTyKWU2vBZT5ZYe?usp=sharing)<br>
(I've trained the model using [Roboflow's Mask Wearing Dataset](https://public.roboflow.ai/object-detection/mask-wearing/1))

# Train
Follow the [notebook](https://github.com/SravanChittupalli/COVID-19-Mask_detector/blob/master/training_yolov4.ipynb) that is included in the repository.

#### Video of results
![Demo Video](https://github.com/SravanChittupalli/COVID-19-Mask_detector/blob/master/Mask_demo.png)

# Tutorials
Roboflow :- [How to Train YOLOv4 on a Custom Dataset](https://blog.roboflow.ai/training-yolov4-on-a-custom-dataset/)
