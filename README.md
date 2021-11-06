![image](https://drive.google.com/uc?export=view&id=1EEbkI9olmXfdFyJhhMa0zI9FjgsodNps)
<div align="center">
<br>
<h3>
Auto-detection of Southern sea otters (Enhydra lutris nereis) from aerial imaging on the Monterey Peninsula
</h3>
<h5>
Margaret Daly, Carlota Pares-Morlans, Mohammed Salman
</h5>
<p>
<i>A project for CS230: Deep Learning, Fall 2021, Stanford University, CA.</i>
</p>
</div>

#### <div align="center">Project Tree</div> 

The main file for this project is ```./src/YOLOv5_SeaOtter_OD.ipynb```. It calls the necessary files from the ```./src/yolov5-master``` folder and trains the baseline model. 

The folder ```./src/utils``` includes some functions that have been used for preprocessing and analyzing the dataset, as well as some helpers for visualizing the outputs.

The folder ```./src/output``` includes the generated plots as well as the log from the training of the model.
```
.
|-- ./sample_dataset
|-- ./src
    |-- ./src/utils
    |-- ./src/YOLOv5_SeaOtter_OD.ipynb
    |-- ./src/output
    `-- ./src/yolov5-master
```

