# EZdrobot_description

## Package ROS 1 pour le projet **Véhicule Mobile Autonome**

### Membres du projet

NACIRI Mehdi
RANDRIAMANANTENA Romain
SCHMITZ Etienne

# Installation

Pour utiliser ce package, il faut avoir installer **ROS Noetic** ansi qu'avoir configuré un espace de travail, ici nommé `catkin_ws`. Les prochaines lignes de code vous permettront d'installer et d'utiliser le package :
    
    cd ~/catkin_ws/src
    git clone https://github.com/Projet-EZ-ROS/EZdrobot_description.git
    cd ~/catkin_ws && catkin_make
    source ~/.bashrc

# Utilisation

Ce package contient une visualisation du robot sous Rviz, une simulation sous Gazebo ainsi que la possibilité de téléopérer le robot sous Gazebo à l'aide des touches `z q s d`.

### Pour lancer la visualisation Rviz :

    roslaunch vma_description vma_rviz.launch

### Pour lancer la simulation Gazebo :

    roslaunch vma_gazebo vma_empty_world.launch

### Pour lancer la téléopération :

    roslaunch vma_teleop vma_teleop.launch