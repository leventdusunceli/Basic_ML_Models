# Determining the Vertebral Column Condition Based on Biomechanical Measurements 

The vertebral column, also known as **the spine**, makes up the central axis of skeleton system in all vertebrates (Kayalioglu, 2009).  

![image](https://user-images.githubusercontent.com/70526402/160996640-6ca28a31-f07f-4583-8d8e-0943542265e1.png)

In this study I aimed to build classification models based on the data set built by Dr. Henrique da Mota (Da Mota, Barreto, & Ajalmar, 2011).  

In the dataset, each patient is represented by six biomechanical attributes of the spine; pelvic incidence, pelvic tilt, lumbar lordosis angle, sacral slope, pelvic radius and grade of spondylolisthesis.  

Each patient is also classified in 2 different ways.  The first classification distinguishes patient's condition as **Normal or Abnormal**. Second classification details abnormal condition and distinguishes the class of patient as either **Normal, Disk Hernia or Spondylolisthesis**.

During the model building phase, we’ll build six different classification models from the ScikitLearn library for both the 2-condition and 3-condition classification and evaluate the performance of the models.   
After model evaluation, we’ll also inspect which attributes seem to contribute the most to the patient’s condition. 



### References
*Da Mota, H., Barreto, G., & Ajalmar, N. (2011). Vertebral Column. UCI Machine Learning Repository. http://archive.ics.uci.edu/ml/datasets/vertebral+column#*

*Kayalioglu, G. (2009). Chapter 3 - The Vertebral Column and Spinal Meninges. The Spinal Cord (s. 17-36). içinde Academic Press. doi:https://doi.org/10.1016/B978-0-12-374247-6.50007-9*



