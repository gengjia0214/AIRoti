# DIRECTORY

## PROJECT BACKGROUND

The global fish consumption has increased by over 100% in the past half decade.
Aquaculture currently contributes more than 50% to the global food-use fish production and is expected to continue
growing. 
Rotifer, a crucial starting diet for fish larvae, is critical for fish aquaculture. 
However, the cultivation of rotifer is labor intensive. 
Automated rotifer culture is one of the necessary and critical piece of next generation aquaculture. 

[[_learn more..._]](background.md)

## WATCH THE DEMO!

__A [demo video](https://youtu.be/5gOE0NdaSRs) of the prototype system is now available!__

The demo video was generated based on the integration of models developed so far: 
- Simple median-based background subtraction for making object proposals 
- Object classification based on ensemble of weak classifiers trained on evolutionary constructed features
- IOU tracking and feature matching-based object re-identification.

For next phase, the focus will be on making the system faster and more accurate, including:
- Collect and annotate more data. 
- Annotate several videos for evaluating the performance of the rotifer tracking and re-identification models.
- Develop deep learning models to achieve better classification accuracy and faster test-time speed.
- Evaluate and improve the object tracking and re-identification model.
- Develop a model to infer the true class of the tracked objects based on tracking history.
- More ideas later...

## PROJECT BLOGs

### BLOG#1 - More About Rotifers and A Glimpse of the Rotifer Dataset

The rotifer dataset is consisted of microscopic images and videos of rotifer culture samples, collected and
annotated by skillful rotifer culture specialists at the University of Miami Experimental Hatchery. 
The dataset is prepared for training classic machine learning algorithms as well as the deep learning models to
achieve the project objectives.

[[_learn more..._]](dataset.md)

### BLOG#2 - Moving Object Detection

Moving object detection algorithm is able to efficiently generate object proposals. The proposed patches can then be
classified by well-trained object classifier into classes of interests. 

[[_learn more..._]](modpc.md)



