
Bone_Dislocation_Identification - v1 2024-03-14 11:48am
==============================

This dataset was exported via roboflow.com on March 14, 2024 at 6:50 PM GM
The dataset includes 30 images.
Dislocation are annotated in COCO format.

OBJECT IDENTIFICATION:  BORN DISLOCATION IDENTIFICATION 
The "Born Dislocation Identification" dataset comprises annotated images illustrating diverse types of bone dislocations in humans. Originally sourced from Kaggle.com under the name "Born Break-In Dataset," it consisted of X-ray images depicting various bone injuries, with particular emphasis on dislocations. Following analysis and refinement, the dataset was tailored to facilitate the accurate identification and classification of bone dislocations. We chose this task because it can help to automate the identification of born injuries in the healthy sector.
We have used tensorflow module to preprocess the images, which creates a prefetch dataset. It also has functions which help to normalize dataset.
We then used roboflow to annotate the images by applying bounding boxes to the parts we are interested in which are the dislocated parts of the bones in the photos we had. This is a site that is used by engineers to create datasets, train models and deploy them as well.
The other libraries that where imported and used where the OS, Numpy, math and matplotlib.




