# IOT

Assignments for IOT Course


### CIA-1
- **Paper: Edge Computing Architectures for Enabling the Realisation of the Next Generation Robotic Systems**
- Link to the notes : [Notes](https://github.com/ash-01xor/IOT-Research-Paper-notes/blob/main/Research%20Paper%20Study.pdf)


### CIA-2
- <b>Smoke detection Analysis</b>:


    Problem statement:

    Design a machine learning model that can predict whether a smoke detector connected to the internet will trigger an alarm or not in response to the presence of smoke. 
    
    The smoke detector is housed in a plastic enclosure, typically shaped like a disk about 150 millimeters (6 in) in diameter and 25 millimeters (1 in) thick. The device is equipped with sensors that can detect the presence of smoke and send this information to a cloud-based platform. 
    
    The platform collects data from multiple smoke detectors and uses machine learning algorithms to analyze the data and identify patterns that indicate the likelihood of a fire. 
    
    The model should take into account factors such as the location of the smoke detector, the time of day, and environmental conditions such as humidity and temperature. 
    
    The goal is to create a model that can accurately predict when a smoke detector will trigger an alarm, reducing false positives and increasing the effectiveness of fire detection in buildings.

    Solution:
    -   Notebook : [Smoke Detection Analysis and Model](smoke-detection-analysis.ipynb)

    Dataset Used:
    - [Dataset](https://www.kaggle.com/datasets/deepcontractor/smoke-detection-dataset)
    - Credits to [Stefan Blattmann](https://github.com/Blatts01) for the collection of data from his DIY sensor.


    The project can be improved by connecting the smoke detectors to a Bluetooth and sensor hub, which can collect data from multiple detectors and transmit it to a central server for analysis. This would improve the functionality of the machine learning model by incorporating additional environmental data and enabling integration with other IoT devices in the building. The hub should be designed to be modular for easy customization and expansion.