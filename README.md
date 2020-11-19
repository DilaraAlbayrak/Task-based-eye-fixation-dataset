# Task-based-eye-fixation-dataset
Eye-fixations of several viewers for different viewing tasks.

## About
We have studied task-based saliency and free-viewing in our work. For that work, we define 3 different tasks and free-viewing as different viewing conditions. We form our content by using 2 different datasets [[1]](#1),[[2]](#2). If you use our fixation data provided here, please cite my master's thesis _'A Study of Visual Saliency for Free-viewing and Task-oriented condition'._

## Dataset
Initially, we prepared an experiment setting with 492 still images from existing datasets. Half of the images were chosen from EMotional Attention Dataset (EMOd) dataset [[1]](#1) and the other half of the images were chosen from Saliency in Crowd (EyeCrowd) [[2]](#2) dataset. Our experiment setting is designed as between-subjects; in total, we have four groups of participants, three of which perform three assigned tasks on the same 492 still images, whereas one group is asked to free-view the same 492 still images. We also referred to free-viewing as a task (the task of no task). Folder names are the same as the below explanation of 4 tasks.
  - For task 1, we asked the participants to count people in the frame, if any, as they can, and come up with a number, the number does not necessarily have to be very exact, the amount that they could count.
  - For task 2, we asked the participants to find an answer for emotion in the frame and people’s feelings in the frame. Before the experiment, some examples are given as 'sad', 'happy', 'angry', etc. and they were also free to choose different words for the emotions as they can think of during viewing.
  - For task 3, the participants were asked to define the occasion in the frame, if any, or what person/people in the frame is/are doing.
  - Task 4 is free-viewing in which the participants were not asked for any task they were told that viewing shown images, freely.

There are 8 participants for each task-based viewing and the free-viewing; in sum, 32 participants joined our experiment. We have conducted the experiment with the 32 participants whose mean age is 25.13 and 13 of them are female, 19 of them are male with normal or corrected-to-normal visual acuity.

## Directory
```stimuli``` folder contains still images from EMOd [[1]](#1) and Saliency in Crowd [[2]](#2) datasets whose names are assigned as randomly generated 5-digit numbers. ```task#``` folders contain corresponding eye-fixation data of task # in which ```fdm``` folders have fixation density maps of eye-fixation data and ```heatmap``` folders have heat maps of eye-fixation data.


## Hardware and Software
We used the SMI eye tracker model of SMI RED-60 Hz with a monitor connected to a DELL laptop to collect gaze data of the participants. The participant viewed still images on a 22" monitor and the eye tracker placed at the bottom of the monitor.

During a participant was viewing given images, eye-tracking software SMI IViewX on the DELL laptop was run and collect data. After all the data collecting is done, fixation density maps are obtained via SMI BEGAZE software.

## References
<a id="1">[1]</a>
  S. Fan, Z. Shen, M. Jiang, B. L. Koenig, J. Xu, M. S. Kankanhalli, and Q. Zhao, “Emotional attention: A study of image sentiment and visual attention,” in Proceedings of the IEEE Conference on computer vision and pattern recognition, pp. 7521–7531, 2018.
  
<a id="2">[2]</a> 
  M. Jiang, J. Xu, and Q. Zhao, “Saliency in crowd,” in European Conference on Computer Vision, pp. 17–32, Springer, 2014.
