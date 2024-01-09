# ELA411 - Neurotechnology Project - Group 1

## Authors
- Carl Larsson
- Pontus Svensson
- Viktor Eriksson

## Project Overview
This project is part of the ELA411 course, focusing on the development of a Brain-Machine Interface (BMI) system. Our group is tasked with creating a standalone BMI system.

### Objective
The main objective is to develop a system capable of recording and acquiring neurophysiological data online using EEG and EMG electrodes. This data will then be decoded to extract navigation commands for controlling a robot in a simulated environment.

## System Requirements
- **Equipment**: Ganglion board with EEG gold-cup and EMG/EKG snap electrodes.
- **Functionality**: Using EMG and EEG data to drive and navigate a robot in a simulated environment.
- **Control Commands**: Decoding of EMG data for directional control (right vs. left) and EEG data for movement initiation (drive vs. don’t drive).

## Acquisition of Neurophysiological Data
- **Setup**: Ganglion board setup is used for recording EEG and EMG activity.
- **Data Streaming**: A communication interface is developed for real-time streaming of EMG and EEG signals with associated timestamps to a computer.
- **Electrode Placement**: Strategic placement of EMG and EEG electrodes is critical for accurate navigation variable decoding.

## Decoding of Data
- **Methodology**: Based on a scientific literature study, we will develop methods for decoding navigation commands from neurophysiological data.
- **Signal Processing**: The acquired signals will undergo noise and artifact reduction processes, followed by feature extraction.
- **AI Implementation**: AI methods will be employed to decode the navigation variables from the processed data.

## Robot Control
- **Simulation Environment**: ROS2 controlled Turtlebot3 robot in Gazebo.
- **Demonstration Scenario**: A repeatable scenario demonstrating the system's functionality across various users.

## Verification and Validation
- The system will undergo verification and validation in accordance with the course instructions.

## Additional Information
- [Ganglion Board Documentation](https://docs.openbci.com/Ganglion/GanglionLanding/)
- [EEG Gold-Cup Active EEG Electrodes](https://docs.openbci.com/ThirdParty/ThinkPulse/ThinkPulse/)

## Note
This project is subject to continuous updates and improvements based on project progress and feedback from our instructors.
