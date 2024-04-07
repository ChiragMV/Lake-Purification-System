# Lake-Purification-System
## Abstract
A project created in 2 days, which can be extended to a large-scale operation.
The creation of an Arduino-based open-source water testing platform marks a notable advancement in water quality monitoring technology. This system, utilizing commercially available sensors and controllers, enables real-time on-site measurements of crucial parameters like water turbidity, acidity (pH), and temperature. Calibration and validation studies, conducted in the laboratory using calibration samples and UV-Vis-NIR absorption spectroscopy, ensure the accuracy and reliability of the measurements, bolstering confidence in its effectiveness. Testing in an artificial lake, alongside comparisons with untreated wastewater samples, demonstrates its practical utility. Moreover, its potential for miniaturization and portability facilitates easy deployment for on-site environmental monitoring, promising significant contributions to environmental assessment and management efforts.

## Author's note:
This project is a basic version of lake purifier. This can be extended with many sensors and varying applications, which is left to user's discretion. The source codes are available in the internet, and can be integrated depending on the user's creativity.

## Introduction, need for purity:
There are many repercussions of industrialization and urbanization on water quality, with issues such as widespread lack of access to clean drinking water.Severity of water contamination is to be emphasised, with millions of children under 5 years old succumbing annually to diseases like diarrhea due to poor water quality.
So, there's a critical need for assessing water quality, which necessitates advanced analytical methods. However, such methods often come with high costs or require significant time investments. Key parameters for evaluating water quality—such as turbidity, temperature, and pH—are to be highlighted. Turbidity serves as an indicator of water clarity and potential contamination, measured through turbidity sensors. Temperature influences aquatic life and oxygen levels, while pH indicates acidity or alkalinity, crucial for overall water quality assessment.
Though these sensors were previously done by dated equipments in lab, due to FOSS(free and open-source software), the sensors can be used to perform the experiment.
This is a project which uses 3 sensors namely, TDS sensor, turbidity sensor, pH sensor, and it assumes temperature as 25 degree celsius, which can be changed using temperature sensor.
To make the project IoT-based, you can also add HC05 bluetooth module, which can send the water quality information to your device, which can be used for further analysis.
## Design & Formula:
Refer to the pictures attached for circuit design.                      
Turbidity value(in NTU) =-1010.59 X 𝑉 + 3820.487                
Individual sensor's source code is attached.
### Problems encountered:
This section is for people encountering similar difficulties:
#### Baud rate:
If you are seeing empty boxes/unknown symbols in the serial monitor instead of the actual output, this is in relation to your baud rate of serial monitor not synchronising with baud rate mentioned in code. It is preferred to change baud rate in serial monitor.
#### Sensor values fluctuating:
For people working with sensors for the first time, it is common for sensor values to fluctuate. But incase of major fluctuations, check your wiring connections.
#### Bluetooth module not working:
This issue is usually related to iPhone users. Android users can easily use the bluetooth module, while this issue persists for other users. This cannot be fixed, with respect to HC05. You can use other methods to send data.
## Further extension:
As stated, you an use a bluetooth module to make this IoT-based. You could also use more components for better analysis keeping in mind the cost-efficiency, since this is to be cost-effective.
## Industrial use:
This setup can be used in industries which produce wastewater. This can be used as a detector for wastes. Incase the turbidity value is high, depending on whether we want the impurities to settle down or froth above, we can use chemical processes like addition of alum, froth flotation. Depending on the type of wastes, we can also do magnetic separation and so on and to achieve this, we can use raspberry pi camera module to detect the wastes. 
## Conclusion:
By utilizing the open-source hardware for on-site water pollution testing, it was made affordable and accessible. The circuit monitored the water quality in an artificial lake fed with treated wastewater. While instrument errors were possible due to various factors, they were minimized through calibration procedures. The temperature and pH sensors provided stable data, but significant deviation was observed in the turbidity sensor, likely due to waterproofing issues. Nevertheless, the device remained cost-effective and portable, facilitating software development. The findings motivate further research on open-source on-site measurement systems, potentially leading to the development of a remote-controlled model ship for continuous water quality monitoring. Expanding the range of water quality sensors could enhance the platform's applicability.
## Acknowledgements:
Online research papers
Stackoverflow, Arduino forum
