# LernFabrik ROS Framework 

|Branch        | Build Status      |
|--------------|-------------------|
|master        |[![CircleCI](https://circleci.com/bb/iwt_lernfabrik/lernfabrik_ros_framework/tree/master.svg?style=svg)](https://circleci.com/bb/iwt_lernfabrik/lernfabrik_ros_framework/tree/master)|
|kinetic       | Master branch is Kinetic|
|melodic       | ToDo              |

## !From here on "master" branch is melodic
### For kinetic new branch called kinetic-dev
# !TODO LIST! 
1. [GIo: iiwa7 is not spawning properly in gazebo 9](https://app.gitkraken.com/glo/board/XKy6W4x6OgARyonM/card/XbLLQTz-owAP0sJB)

# Error List
1. [Koni Port is not stable enough](https://app.gitkraken.com/glo/board/XKy6W4x6OgARyonM/card/XbLLQTz-owAP0sJB)
    * For more details follow the [link.](https://github.com/IFL-CAMP/iiwa_stack/issues/7)
    * Possible solution because the commmand not workin properly: C:\KUKA\Hardware\Manager\KUKAHardwareManager.exe -assign OptionNIC -os RTOS 
2. Linear motion error
    ![Error](https://bitbucket.org/iwt_lernfabrik/lernfabrik_ros_framework/src/master/Doc/Linear_motion_error.png)