# Machine learning robot

The machine learning bot is a project of making an OpenSource robot that will be able to learn from its environment and adapt to it using machine learning.

The robot is based on a FREENOVE ESP32 S3 MCU and its camera. It also includes a LIDAR.
The mechanical part is based on a Adafruit 3216 chassis.

## Electronics

### Electronics components

The robot is based on a [FREENOVE ESP32 S3](https://github.com/Freenove/Freenove_ESP32_S3_WROOM_Board).

In addition to the included camera, we bought [this camera](https://www.amazon.fr/gp/product/B0BXSL76L8/ref=ewc_pr_img_1?smid=AFDYUAFSP3DOA&psc=1). The ribbon cable is longer than the included one and it allows to position it on the front of the robot.

The LIDAR used is a LD06 from innomaker ([datasheet](https://www.inno-maker.com/wp-content/uploads/2020/11/LDROBOT_LD06_Datasheet.pdf)).

### PCB

The chassis chosen is very tiny. It includes only two frame for two stages. To gain space, we decided to build and make a full PCB stage. Allowing the robot to go from 2 to 3 stages.

The PCB project can be found in the [pcb](https://github.com/matthieu-sgi/machine_learning_robot/tree/main/PCB) folder.

3D view of the PCB:

Front 3D view | Back 3D view
:------------:|:------------:
![Front 3D view](/media/3D_view_front.png) | ![Back 3D view](/media/3D_view_back.png) 
