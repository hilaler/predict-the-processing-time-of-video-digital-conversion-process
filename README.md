# predict-the-processing-time-of-video-digital-conversion-process

# Problem 1
In this problem, you are asked to deliver a data science solution to predict the processing time of video digital conversion process. The process time has divided into several categories, which are Fast, Medium, and Slow. The variable explanations are below:
- video: ID of the video
- duration: duration of the video (second)
- width: the width of the video (pixels)
- height: the height of the video (pixels)
- frame_class: the video framerate class
a. Low Framerate: 5-20 frames per second
b. High Framerate: 20-60 frames per second
- bitrate: the number of bits per second
- intracoded_frame: intracoded picture (frames)
- predicted_frame: predicted picture (frames)
- total_frame: total of intracoded frame and predicted frame
- intracoded_size: total size of intracoded_frame (bytes)
- predicted_size: total size of predicted_frame (bytes)
- total_size: total of intracoded_size and predicted size
- codec: the codec form of the video
- tc_width: the width of video after transcoding (pixels)
- tc_height: the height of video after transcoding (pixels)
- tc_frame_class: the transcoding video framerate class
a. Low Framerate: 5-20 frames per second
b. High Framerate: 20-60 frames per second
- tc_bitrate: the number of bits per second after transcoding
- label: classification of a processing time

# Problem 2
In this problem, you are asked to analyze an event data of a process mining for a purchasing process in an organization. In this data, there are several variables which are Case ID, Activity, Start Timestamp, Complete Timestamp, Activity, Resource, and Role.
a. Find how many cases that end with “Pay Invoice” Activity
b. Find how many cases that don’t end with “Pay Invoice” Activity
c. Find average duration of the case that end with “Pay Invoice” Activity
d. Find all the last activity of the case that don’t end with “Pay Invoice” Activity
e. Find all case that has only “Pedro Alvares” as a “Financial Manager”
f. Find all case that has “Settle dispute with supplier Purchasing Agent” in one of its activities
