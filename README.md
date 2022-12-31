# Dataset
## CADAVER
A new depth estimation dataset about robotic laparoscopy. The dataset provides endoscopic videos and corresponding robot kinematics for surgical scene depth estimation and reconstruction.

We conducted a cadaver experiment in Prince of Wales Hospital, Hong Kong, to collect the surgical scene depth estimation dataset about robotic laparoscopy. The cadaver experiment was performed on a robot-based laparoscopic platform composed of a UR5 robot and an Olympus endoscope imaging system. The Olympus endoscope is attached at the end of the robot so the endoscope can be automatically controlled by the robot. During the laparoscope movement, stereo videos about the abdominal cavity are recorded at 25 fps with a standard resolution of $1920 \times 1080$ pixels, and the corresponding robot kinematics are also stored. Besides, we did a high-quality stereo calibration for the laparoscope and a hand-eye calibration between the robot and the laparoscope during the experiment. Based on the calibrated stereo images and the stereo dense reconstruction method \cite{wei2022stereo}, the depth map for each frame and the whole 3D structure of the abdominal cavity are computed. Since the accuracy of the method has been validated, we consider the depth maps and 3D structures as ground truth.

# Code
