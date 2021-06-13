# basic_mission_gazebo

This project executes a simple mission using Gazebo simulator. 
In order to execute this project, follow the steps below.


- Execute the script from the project directory that launches Gazebo:

        $ ./launcher_gazebo.sh

- Wait until the following window is presented:

![Gazebo simulator interface with drone ](https://i.ibb.co/XV1hYDy/Captura-de-pantalla-de-2021-06-07-11-16-42.png)

- Open a new terminal and change directory to the project

- Execute the script that launches the Aerostack components for this project:
 
        $ ./main_launcher.sh

- Execute the following command to run the mission:

        $ rosservice call /drone111/python_based_mission_interpreter_process/start

- To stop the processes execute the following script:

        $ ./stop.sh

- To close the inactive terminals:

        $ killall bash

The following video illustrates how to launch the project:

[ ![Launch](https://i.ibb.co/6Jp3shp/basic-mission-launch-Moment.jpg)](https://youtu.be/D5i7wXEs7dM)

The following video shows the mission execution:

[ ![Launch](https://i.ibb.co/K9rvDXN/basic-mission-gazebo-v2-Moment.jpg)](https://youtu.be/rW2DMaljw-A)

