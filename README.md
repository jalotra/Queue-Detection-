# Queue-Detection

## Current Tasks 
Yolo from here : https://github.com/ultralytics/yolov5
1. To use the YOLO Algorithm to detect all the bounding boxes that are persons.
2. Reading the Source Code of Darknet, learning about Yolo Layers and the implementation in Pytorch.  
3. Maybe Fine Tune the Model to only output bounding boxes around humans. Something like this : https://www.codeproject.com/Articles/5283660/AI-Queue-Length-Detection-Counting-the-Number-of-P



## Setting Up the Development Arena 
1. You must have Conda installed, since it provides containerisation we dont have to worry about building and running on Different Platforms/ OSes.
2. First run "bash setup_env.sh" -> This will create a `Queue_Detection` conda environment.
3. Run `conda activate Queue_Detection` to activate the newly made env.
2. Next run "bash setup.sh" -> This will install all the related dependencies.
2. In case of error, read the *sh files and figure it out yourself.

## Average Timings on Still Images
1. Yolov5s - 
2. Yolov5m - 
3. Yolov5l - 
4. Yolov5x - 
5. Yolov5x + TTA - 

## Datasets to Check On 
1. Shanghai DataSet : https://www.kaggle.com/tthien/shanghaitech
2. 


## Readings : 
Ques : Why are there different versions of the same paper ? 
1. V1 : https://arxiv.org/pdf/1506.02640v1.pdf 
2. V2 : Somrthing  Here
3. V3 : Something Here 
4. V4 : https://arxiv.org/pdf/1506.02640v4.pdf
5. https://blog.paperspace.com/how-to-implement-a-yolo-object-detector-in-pytorch/


## Results : 
Picture 1 : 

![Indian Queue](/src/yolo/results/indian_bank_4_result.jpg)

Picture 2 : 

![Indian Queue](/src/yolo/results/indian_bank_3_result.jpg)

Picture 3 : 

![Indian Queue](/src/yolo/results/indian_bank_result.jpg)

Picture 4 : 

![Indian Queue](/src/yolo/results/indian_ban_2_result.jpg)

Picture 5 :

![Not Indian Queue](/src/yolo/results/american_bank_result.jpg)