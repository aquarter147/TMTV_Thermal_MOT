# Thermal_MOT
Multiple-Object Tracking (MOT) is a fundamental task in computer vision with
many applications. For practical operations, real-time tracking for monitoring
with thermal imaging unaffected by lighting conditions is important. However,
most MOT methods are proposed to analyze video streams from RGB cameras,
while there are few datasets and research on multi-object tracking in infrared
image sequences. In this paper, we provide a new infrared dataset for object
detection and tracking, which contains small objects and occlusion challenges.
We also propose a new robust tracker, which enhances object detection and data
association to overcome the challenges of thermal images in real time.


# Dataset
Dataset is stored at: 
The dataset is divided into training and testing subsets, with 13 sequences for training
and 5 sequences for testing. Each sequence is organized in a dedicated folder that
contains gt.txt, an images folder with all the frames, and a seqinfo.ini file that
provides metadata about the sequence. The gt.txt file includes detailed annotations
for every frame, and each line in this file follows the format: frame id, track id,
x, y, w, h, class. This organized structure is designed to facilitate easy access and
usability for researchers working on object tracking in infrared imagery.

Each bounding box
was assigned a track ID and class label to maintain consistency across frames. The
class labels used in the annotation include person, bike, car, ship, and animal,
corresponding to IDs 1, 2, 4, 5, and 6, respectively. 
