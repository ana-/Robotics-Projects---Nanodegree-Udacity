# Robotics-Projects---Nanodegree-Udacity
Udacity robotica nanodegree designs
The goals / steps of this project are the following:

Training / Calibration

    Download the simulator and take data in "Training Mode"
    Test out the functions in the Jupyter Notebook provided
    Add functions to detect obstacles and samples of interest (golden rocks)
    Fill in the process_image() function with the appropriate image processing steps (perspective transform, color threshold etc.) to get from raw images to a map. The output_image you create in this step should demonstrate that your mapping pipeline works.
    Use moviepy to process the images in your saved dataset with the process_image() function. Include the video you produce as part of your submission.

Autonomous Navigation / Mapping

    Fill in the perception_step() function within the perception.py script with the appropriate image processing functions to create a map and update Rover() data (similar to what you did with process_image() in the notebook).
    Fill in the decision_step() function within the decision.py script with conditional statements that take into consideration the outputs of the perception_step() in deciding how to issue throttle, brake and steering commands.
    Iterate on your perception and decision function until your rover does a reasonable (need to define metric) job of navigating and mapping.


Rubrics

Notebook Analysis
I am a difficulty in starting the installation of my environment without the administrator of the access, when it was not possible to access the jupyter notebook, I asked for help through live help and the mentor Pacencia in explaining the problem to me, from the project project.

Describe in your writeup how you modified the process_image() to demonstrate your analysis and how you created a worldmap. Include your video output with your submission.]

I found problems related to creating new files, I restored the github code RoboND master but I could not solve it, I started to study about the movie.py library but I ended up reinstalling my simulator. It worked but the creation of my video is very slow, I saw that the dimension that we recorded of the simulator influences a lot in the processing of the images.

Links help me: http://www.scipy-lectures.org/packages/scikit-image/
http://www.pyimagesearch.com/2014/08/25/4-point-opencv-getperspective-transform-example/


perception_step() and decision_step() functions have been filled in and their functionality explained in the writeup. 

I've been studying python for a while now and I already have a certain notion of using classes, as I study computer science here in Brazil at the Pontificia Universidade Catolica in Rio de Janeiro, and I've already studied a subject called basic software, which deals with Low level in development, I used the C language and learned a lot about bit usage, bitwise and everything else so I tested the use in perception, trying to generate a certain fidelity in the code. My code in the first test with 1024x768 could not recognize anything which made me a bit frustrated.



In decision.py I found a certain difficulty because all the algorithms of decisions that I tested the cart did not respond, sometimes my logic was wrong, for delivery I decided to follow with the "spoiler" given in the video but I intend to reissue the project, because I want to try To use the algorithm A * and maybe there is my difficulty in trying directly to use this algorithm in the decision making.

By running drive_rover.pyand launching the simulator in autonomous mode, your rover does a reasonably good job at mapping the environment. 


I tested it with 1024x768 and ran beautifully 25 frames per second. In standalone mode I realized that very high resolution impairs the visibility of the project on my laptop. I tested with 800x600  And I noticed that ground speed slows down

This challenge was great for me, please, much work with robotics and artificial intelligence and with every mistake I want to solve as quickly as possible, learning the patience and the key to knowledge. It was in law to know that it is a nasa challenge, I looked for more about it, because I did not know it.
Need to improve my map a bit, I want to put the different cores, collect as rocks and improve my decision making, I believe that using the algorithm A * will be a challenge for me and also a huge learning. I sure will use the slack to get a lot of questions about.
Note: running the simulator with different choices of resolution and graphics quality may produce different results, particularly on different machines! Make a note of your simulator settings (resolution and graphics quality set on launch) and frames per second (FPS output to terminal by drive_rover.py) in your writeup when you submit the project so your reviewer can reproduce your results.
