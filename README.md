# Push Recovery on a LIPM of a Biped with variable velocity gait, controlled using MPC

In this project, the 1D Linear Inverted Pendulum Model (LIPM) of a biped was controlled by a Model Predictive Controller (MPC) with a variable velocity gait. By tracking the Instantaneous Capture Point, it was possible to implement push recovery to the model. The model, and the observations are explained in better detail in the [Report](https://github.com/thathvik/Push_Reovery_LIPM_biped/blob/master/Report.pdf).

This is the final project submitted for the course *Optimal and Learning Control* (ME-GY 7973), as done by Tarun Thathvik Paladugu. This project expands on the previous work on [Model Predictive Control](https://github.com/thathvik/optlearningcontrol/blob/master/Series3/Series_3_exercise_1.ipynb) of the LIPM in the Exercise Series 3. The instructions to run/modify the variables are given in the [Notebook file](https://github.com/thathvik/Push_Reovery_LIPM_biped/blob/master/Final_Project.ipynb).

The video below demonstrates the results from the project.

https://user-images.githubusercontent.com/42662610/125012057-88549600-e037-11eb-9e25-dec815ffc927.mp4

During the first half of the video, the change in the speed of the biped can be observed. And during the second half of the video, the biped experiences a push force and it can be observed that the controller could handle the force and bring the robot back to the motion at the desired veloicity.
