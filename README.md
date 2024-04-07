# Lake-Purification-System
## Abstract
A project created in 2 days, which can be extended to a large-scale operation.
The creation of an Arduino-based open-source water testing platform marks a notable advancement in water quality monitoring technology. This system, utilizing commercially available sensors and controllers, enables real-time on-site measurements of crucial parameters like water turbidity, acidity (pH), and temperature. Calibration and validation studies, conducted in the laboratory using calibration samples and UV-Vis-NIR absorption spectroscopy, ensure the accuracy and reliability of the measurements, bolstering confidence in its effectiveness. Testing in an artificial lake, alongside comparisons with untreated wastewater samples, demonstrates its practical utility. Moreover, its potential for miniaturization and portability facilitates easy deployment for on-site environmental monitoring, promising significant contributions to environmental assessment and management efforts.

## Introduction
### Need for purity:
There are many repercussions of industrialization and urbanization on water quality, with issues such as widespread lack of acces to clean drinking water.Severity of water contamination is to be emphasised, with millions of children under 5 years old succumbing annually to diseases like diarrhea due to poor water quality.
So, there's a critical need for assessing water quality, which necessitates advanced analytical methods. However, such methods often come with high costs or require significant time investments. Key parameters for evaluating water quality—such as turbidity, temperature, and pH—are to be highlighted. Turbidity serves as an indicator of water clarity and potential contamination, measured through turbidity sensors. Temperature influences aquatic life and oxygen levels, while pH indicates acidity or alkalinity, crucial for overall water quality assessment.
Though these sensors were previously done by dated equipments in lab, due to FOSS(free and open-source software), the sensors can be used to perform the experiment.
This is a project which uses 3 sensors namely, TDS sensor, turbidity sensor, pH sensor, and it assumes temperature as 25 degree celsius, which can be changed using temperature sensor.
To make the project IoT-based, you can also add HC05 bluetooth module, which can send the water quality information to your device, which can be used for further analysis.
### Design:
Refer to the pictures attached for circuit design.
### Formulae:
Turbidity value ሺin NTUሻ ൌ െ1010.59 ൈ 𝑉 ൅ 3820.487(
