Algorithm of Lord's Eye:

STEP - 1
Mount Google Drive

STEP - 2
Load the video
Capture the frames (For our submission purpose, we have used 5) for slot detection.
Find Frequency of cars and compare it with defined threshold to produce a map  

STEP - 3
Display the rectangle drawn on detected slots.

STEP - 4
Save the co-ordinates in CSV file.

STEP - 5
Load the co-ordinates from CSV file 
Crop the given test image according to given RegionOfInterest

STEP - 6
Apply the model and get the results (center co-ordinates of the slot,occupied/not-occupied,color_code,pos)
Show the test image with Red & Green rectangles with center points



NOTE:
frozen_inference_graph.pb file being too large is not included in this repository (in mask-rcnn/mask-rcnn-coco folder)
