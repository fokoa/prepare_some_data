
=========================================
Air Quality Data Set

link : https://archive.ics.uci.edu/ml/datasets/Air+Quality
=========================================



=========================================
Source
=========================================

Saverio De Vito 
saverio.devito@enea.it

ENEA - National Agency for New Technologies, Energy and Sustainable Economic Development


=========================================
Data Set Information 
=========================================

The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an 
Air Quality Chemical Multisensor Device. The device was located on the field in a significantly polluted area, at road 
level,within an Italian city. Data were recorded from March 2004 to February 2005 (one year)representing the longest freely 
available recordings of on field deployed air quality chemical sensor devices responses. Ground Truth hourly averaged 
concentrations for CO, Non Metanic Hydrocarbons, Benzene, Total Nitrogen Oxides (NOx) and Nitrogen Dioxide (NO2) and were 
provided by a co-located reference certified analyzer. Evidences of cross-sensitivities as well as both concept and sensor drifts 
are present as described in De Vito et al., Sens. And Act. B, Vol. 129,2,2008 (citation required) eventually affecting sensors 
concentration estimation capabilities. Missing values are tagged with -200 value.
This dataset can be used exclusively for research purposes. Commercial purposes are fully excluded.


=========================================
Files
=========================================

	- AirQualityUCI.xlsx
	- AirQualityUCI.csv
	

=========================================
Attribute Information
=========================================	
	
	0 Date (DD/MM/YYYY)
	1 Time (HH.MM.SS)
	2 True hourly averaged concentration CO in mg/m^3 (reference analyzer)
	3 PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)
	4 True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer)
	5 True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)
	6 PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)
	7 True hourly averaged NOx concentration in ppb (reference analyzer)
	8 PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)
	9 True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)
	10 PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)
	11 PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted)
	12 Temperature in Â°C
	13 Relative Humidity (%)
	14 AH Absolute Humidity
	
=========================================
License
=========================================
Use of this dataset in publications must be cited to the following publication:

[1] S. De Vito, E. Massera, M. Piga, L. Martinotto, G. Di Francia, On field calibration of an electronic nose for benzene estimation in an urban pollution monitoring scenario, Sensors and Actuators B: Chemical, Volume 129, Issue 2, 22 February 2008, Pages 750-757, ISSN 0925-4005,

@article{DEVITO2008750,
title = {On field calibration of an electronic nose for benzene estimation in an urban pollution monitoring scenario},
journal = {Sensors and Actuators B: Chemical},
volume = {129},
number = {2},
pages = {750-757},
year = {2008},
issn = {0925-4005},
doi = {https://doi.org/10.1016/j.snb.2007.09.060},
url = {https://www.sciencedirect.com/science/article/pii/S0925400507007691},
author = {S. {De Vito} and E. Massera and M. Piga and L. Martinotto and G. {Di Francia}},
keywords = {Electronic nose, Multi-sensor device, Urban atmospheric pollution, Benzene monitoring, Artificial neural networks, On-line calibration},
abstract = {Low-cost gas multi-sensor devices could be efficiently used for densifying the sparse urban pollution monitoring mesh if equipped with a reliable calibration able to counter specificity and stability issues of solid-state sensors they rely on. In this work, we present a neural calibration for the prediction of benzene concentrations using a gas multi-sensor device (solid-state) designed to monitor urban environment pollution. The feasibility of a sensor fusion algorithm as a calibrating tool for the multi-sensor device is discussed. A Conventional air pollution monitoring station is used to provide reference data. Results are assessed by means of prediction error characterization throughout a 13 months long interval and discussed. Relationship between training length and performances are also investigated. A neural calibration obtained using a small number of measurement days revealed to be capable to limit the absolute prediction error for more than 6th month, after which seasonal influences on prediction capabilities at low-concentrations suggested the need for a further calibration.}
}

=========================================
Contact
=========================================
	
For further information about this dataset please contact Saverio De Vito (saverio.devito@enea.it)
