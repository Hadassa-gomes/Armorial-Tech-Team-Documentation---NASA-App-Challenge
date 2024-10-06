# Armorial-Tech-Team-Documentation---NASA-App-Challenge
Repository Created by the Armorial Tech Team for Documentation of the NASA App Challenge Hackathon
SOFTWARE ARCHITECTURE DOCUMENTATION - FIRE FOCUS


OVERVIEW
Fire Focus is designed to analyze and predict occurrences involving forest fires in areas susceptible to these phenomena, using various meteorological indices and soil and vegetation moisture levels. The data system provides accurate and up-to-date information, enabling more precise decision-making for more effective actions.
Additionally, wildfires affect not only the vegetation of an area but also degrade human and animal life, causing a process of forced migration. Because forced migration due to forest fires is a growing issue, Fire Focus aims to address this problem through predictive analyses and detailed reports.
Wildfires have caused economic and social impacts due to population displacement and loss of income, which are just some examples of how wildfires directly affect human life. 
For this reason, Fire Focus provides interactive maps that highlight and alert about areas most susceptible to fires. Additionally, it offers data analysis to predict the likelihood of fires in vulnerable areas, along with issuing alerts and recommendations to prevent potential disruptions caused by wildfires. 


MAIN COMPONENTS OF THE SYSTEMS
 1- Figma technology for prototyping and building the visual elements of our application. (config 2024 version)
2- QGIS (Quantum Geographic Information System): An open-source and free Geographic Information System (GIS) for editing, analyzing, and managing spatial data. (3.34.11-Prizren version)
3- Base de dados cedidas pela NASA a partir dos protocolos: 
CESM2 (Community Earth System Model Version 2)
HadGEM3-GC31-LL (Hadley Centre Global Environment Model Version 3)
DataSet GDDP-IMPACT


FIRE PREDICTION INDICES
BUI (Build-Up Index) -Measures the accumulated fuel over time.
 DC (Drought Code) Measures the moisture content of heavy fuels and soil.
 DMC (Drought Moisture Code) Description: Measures the moisture content of fine fuels.
 FFMC (Fine Fuel Moisture Code) Measures the moisture content of fine fuels such as grass and leaves.
FWI (Fire Weather Index) A global index that combines meteorological factors.
Components:
N15, N30, N45: Values for 15, 30, and 45 days.
NMID: Normalized relative humidity.
NP95: 95th percentile of precipitation.


ISI (Initial Spread Index) Measures the initial rate of fire spread.


 IMPLEMENTATION FLOW
Data Collection: Integration with meteorological APIs for real-time weather and moisture data.
Index Calculation: Recalculates the indices at each interval (5 years).
Data Storage: Results stored in the database for historical analysis.


 STEP-BY-STEP FOR  THE  USER
Access to the System: Access the platform.
Select Monitoring Area: Choose the geographical area.
Check Indices: Display the indices.
 FINAL CONSIDERATIONS
The implementation of Fire Focus is crucial for predicting and mitigating forest fires, providing effective tools for risk analysis.


REFERENCE
Environmental Disasters and Environmental Refugees: Parameters for Sustainable Human Development. Accessed on: https://periodicoseletronicos.ufma.br/index.php/bauman/article/view/18072


How Do Amazon Wildfires Impact Migration and Refugees? Accessed on:  https://sbsa.com.br/como-as-queimadas-na-amazonia-impactam-a-migracao-e-os-refugiados/ 


Data GPD-IMPACT. Acessed on: https://data.nas.nasa.gov/gddpimpact 



