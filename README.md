# TMTV Thermal-MOT Dataset
This is the repository for the TMTV Thermal-MOT Dataset, a dataset proposed in our paper **Advancing Thermal Multi-Object Tracking with Attention and Metric Fusion** which is under review.

## Introduction

We introduce TMTV, an extensive dataset for multi-object detection and tracking in infrared imaging, which includes data from both land and maritime environments. The dataset contains 18 sequences of thermal infrared images, featuring 2,692 frames with over 15,000 bounding boxes with 5 different classes, captured at 640 x 480 resolution. The dataset is divided into 13 training sequences and 5 test sequences.

Our YOLOv7+CBAM object detector achieved a mAP50 and mAP score of 76.6 and 47.4, respectively, while our documented tracking method achieved an accuracy of 59.96 HOTA, 52.42 MOTA and 69.37 IDF on the test sequences of the dataset. 

## Dataset Format

Each sequence is organized in a dedicated folder that contains `gt.txt`, an `images` folder with all the frames, and a `seqinfo.ini` file that provides metadata about the sequence. The `gt.txt` file includes detailed annotations for every frame, and each line in this file follows the format: `frame_id, track_id, x, y, w, h, class`.

The dataset features 5 different classes of objects, with class IDs `1`, `2`, `4`, `5`, and `6` representing `person`, `bike`, `car`, `ship`, and `animal` in the annotations, respectively.

## Dataset Access

### Google Drive
Link: [https://drive.google.com/file/d/1Sv4acnazzl1vVELslddoosEMe2_4y841/view?usp=sharing](https://drive.google.com/file/d/1Sv4acnazzl1vVELslddoosEMe2_4y841/view?usp=sharing)

## References

[1] Thao-Anh Tran, Vu-Minh Le, Thanh-Tung Phan et al. Advancing Thermal Multi-Object Tracking with Attention and Metric Fusion, 01 December 2024, PREPRINT (Version 1) available at Research Square [https://doi.org/10.21203/rs.3.rs-5408058/v1]
