<div align="center">
  <img src="https://github.com/Hamed-Aghapanah/4_Yolo_localizer_Cardiac/blob/main/000.PNG" width="600"/>
  <div>&nbsp;</div>
  <div align="center">
    <b><font size="5">Hamed Aghapanah </font></b>
    <sup>
      <a href="https://HamedAghapanah.com">
        <i><font size="4">HOT</font></i>
      </a>
    </sup>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <b><font size="5">HamedAghapanah platform</font></b>
    <sup>
      <a href="https://HamedAghapanah.com">
        <i><font size="4">TRY IT OUT</font></i>
      </a>
    </sup>
  </div>



      <div align="center">
  <div style="float:left;margin-right:10px;">
  <img src="https://github.com/Hamed-Aghapanah/4_Yolo_localizer_Cardiac/blob/main/all_datasets_d.gif" width="380px"><br>
    <p style="font-size:4.5vw;"> Cardiac MRI Localization with YOLO </p>
  </div>
 <div align="left"> 
 <font size="40"> Cardiac Localization with YOLO

This repository contains code and instructions for implementing cardiac localization using YOLO (You Only Look Once), a popular object detection algorithm.
## Table of Contents

    Introduction
    Requirements
    Installation
    Usage
    Training
    Testing
    Results
    License
    Acknowledgments

## Introduction

Briefly introduce the project and its purpose. Explain why cardiac localization with YOLO is relevant and provide a high-level overview of the implementation.
Requirements

List the software and hardware requirements necessary to run the code. Include specific versions if applicable.

    Python 3.x
    YOLOvX (replace X with the version you are using)
    CUDA and cuDNN (if using GPU)
    Additional dependencies (list them)

## Installation

```shell
git clone https://github.com/your-username/cardiac-localization-yolo.git
# Change into the project directory
cd cardiac-localization-yolo
# Install dependencies
pip install -r requirements.txt
python detect_cardiac.py --image_path /path/to/image.jpg
python train.py --data /path/to/training_data --config /path/to/config_file
python test.py --model /path/to/trained_model --test_data /path/to/test_data
```
## Results
<div align="center">
  <img src="https://github.com/Hamed-Aghapanah/4_Yolo_localizer_Cardiac/blob/main/F1_curve.png" width="200"/>
  <img src="https://github.com/Hamed-Aghapanah/4_Yolo_localizer_Cardiac/blob/main/PR_curve.png" width="200"/>
  <img src="https://github.com/Hamed-Aghapanah/4_Yolo_localizer_Cardiac/blob/main/P_curve.png" width="200"/>
  <img src="https://github.com/Hamed-Aghapanah/4_Yolo_localizer_Cardiac/blob/main/R_curve.png" width="200"/>
</div>  

   
 <div align="center"> 
   test_batch1_pred
   <font size="10">
 </div>
    <div align="center">  
  <img src="https://github.com/Hamed-Aghapanah/4_Yolo_localizer_Cardiac/blob/main/test_batch1_pred.jpg" width="600"/>
   </div> 

   
   <div align="center"> 
   <font size="10">
   train_batch8 
     </div> 

     
   <div align="center"> 
  
  <img src="https://github.com/Hamed-Aghapanah/4_Yolo_localizer_Cardiac/blob/main/train_batch8.jpg" width="600"/>
        </div> 
        <div align="center"> 
   <font size="10">
          test_batch0_pred
          </div> 
   <div align="center"> 

  <img src="https://github.com/Hamed-Aghapanah/4_Yolo_localizer_Cardiac/blob/main/test_batch0_pred.jpg" width="600"/>

</div>  

Include information about the results obtained using the trained model. Display sample outputs and metrics.
License

This project is licensed under the MIT License.
Acknowledgments

Give credit to any external libraries, datasets, or resources used in the project.
