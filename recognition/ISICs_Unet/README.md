# Segment the ISICs data set with the U-net

## Project Overview
This project aim to solve the segmentation of skin lesian (ISIC2018 data set) using the U-net, with all labels having a minimum Dice similarity coefficient of 0.7 on the test set.

## data set structure

data set folder need to be stored in same directory with structure same as below
```bash
ISIC2018
  |_ ISIC2018_Task1-2_Training_Input_x2
    |_ ISIC_0000000
    |_ ISIC_0000001
    |_ ...
  |_ ISIC2018_Task1_Training_GroundTruth_x2
    |_ ISIC_0000000_segmentation
    |_ ISIC_0000001_segmentation
    |_ ...
```