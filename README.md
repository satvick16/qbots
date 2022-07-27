# QBots

This repository contains the Simulink models and research papers I used while working with the Quanser QBots as part of my summer research internship at the University of Toronto under Professor Deepa Kundur and Professor Mohammad Al Janaideh.

Our research was focused on using transformer networks to classify faults in connected autonomous vehicle platoons.

I used the QBots to simulate a variety of faults including:
- motor disturbances
- burst transmission
- denial-of-service (DoS) attack
- drunk driver
- distracted driver

I was then able to use the bots to collect velocity data that was used as testing data for our neural network.

## Contents

- 1_setup: contains building block code to perform simple operations such as inverse kinematics and teleoperation of the robots
- 2_autonomous_faults: implementing faults that affect autonomous vehicles in the platoon (motor disturbances, burst transmission, denial-of-service (DoS) attack)
- 3_human_faults: implementing faults that affect autonomous vehicles in the platoon (drunk driver, distracted driver)
- 4_data_collection: models used for collecting velocity data of a platoon