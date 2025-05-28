Dataset: DAE fingerprints 2025
### by Marcin Kolakowski (Warsaw University of Technology, Warsaw, Poland)

[![CC BY 4.0][cc-by-shield]][cc-by] 

<img src="description/img/poses.png" alt="Measurement points" width="300"/>


A dataset of WiFi fingerprints collected in May 2025 with dynamic accuracy estimation in mind. The dataset includes:
* 359 fingerprints collected in 117 points using a robotic platform equipped with Samsung A41 smartphone mounted at 74 cm above the floor level. (`robot_fingerprints.csv`)
* 117 fingerprints collected in 27 points by a user using the same Samsung A41. (`user_fingerprints.csv`)

The dataset was collected at the Warsaw University of Technology (FEIT building). The reference locations were obtained with a lidar (robot) and a laser distance meter (user).

The dataset also includes the occupancy gridmap created using the robot (`gridmap.png`). The (0,0) point corresponds to (80, 400) pixel. The map has a resolution of 0.05 m and spans  [-4.0, 14.85, -6.7, 20.0] cooridinates (in meters).

The dataset was created with training Dynamic Accuracy Estimation methods. It has been used in the following publications:
 * a paper submitted to the Polish conference KRiT 2025.
 
 
This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg