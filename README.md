<div align="center">
<br>
<h3>
Auto-detection of Southern sea otters (Enhydra lutris nereis) from aerial imaging on the Monterey Peninsula
</h3>
<h4>
Margaret Daly, Carlota Pares-Morlans, Mohammed Salman
</h4>
<p>
<i>A project for CS230: Deep Learning, Fall 2021, Stanford University, CA.</i>
</p>
</div>

#### <div align="center">Project Tree</div> 

The main file for this project is ```./src/YOLOv5_SeaOtter_OD.ipynb```. It calls the necessary files from the ```./src/yolov5-master``` folder and trains the modified YOLOv5 model for small object detection. 

The folder ```./src/utils``` includes some functions that have been used for preprocessing and analyzing the dataset, as well as some helpers for visualizing the outputs.
```
.
|-- ./sample_dataset
|-- ./src
    |-- ./src/utils
        |--./Sea_Otter_Error_Analysis.ipynb
    |-- ./src/YOLOv5_SeaOtter_OD.ipynb
    `-- ./src/yolov5-master
```
![image](https://drive.google.com/uc?export=view&id=1EEbkI9olmXfdFyJhhMa0zI9FjgsodNps)
