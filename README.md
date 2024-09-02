# TADS
TADS is a novel dataset for road traffic accident detection from the surveillance perspective, it consists of a total of 259,891 video frames.
We have released the TADS dataset and you can download it from [here](https://pan.baidu.com/s/1rHJZeWSScDArCAW_bCPSMA?pwd=id6g). (Extraction code: id6g).  
The folder on this link contains three files:  
rgb_frames.zip: video frames in the form of 20 long videos;  
fixation.zip: eye-tracking data corresponding to the video frames;  
label_ta_upload.xlsx: the label file.  
We recommend that you can first organize the video frames into 966 accident frame files according to the scenario starting and ending positions in the .xlsx file of every accident segment in long video. Then you can split the training and testing set based on the train_test_split.pkl file. For more information about each attribute in the label file, please refer to our paper.  
Here are some accident frame examples:
![Image example](https://github.com/cyc-gh/TADS/blob/main/img-folder/snapshots_accidents.PNG)
## Citation
If you found the dataset is useful, please cite our paper:  
Chai Y, Fang J, Liang H, et al. TADS: a novel dataset for road traffic accident detection from a surveillance perspective[J]. The Journal of Supercomputing, 2024: 1-24.

