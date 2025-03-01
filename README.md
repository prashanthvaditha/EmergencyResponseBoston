## Optimizing Emergency Response Times in Boston Using GIS
# Project Overview
This project analyzes crime hotspots and emergency response times in Boston to determine optimal locations for new police stations.

### Crimes Dataset: https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system/resource/b973d8cb-eeb2-4e7e-99da-c92938efc9c0
 
### Tools & Software Used
ArcGIS Pro (Network Analyst Extension)
Location-Allocation Analysis
Kernel Density Analysis (for crime hotspots)
Service Area Analysis (for response time mapping)

### Steps
1) Located all the police stations in Boston and added them to ArcGIS Map, then performed Network Analysis, setting the drive-time as 5 minutes.      
 ![PoliceStations5minDriveTime](https://github.com/prashanthvaditha/EmergencyResponseBoston/blob/main/policedrivetime5.gif)
  
2) Based on the 2023-2025 crime dataset, performed optimized Hot Spot Analysis in ArcGIS.
 ![result](https://github.com/prashanthvaditha/EmergencyResponseBoston/blob/main/crimehotspot.gif)
   
3) Identified areas with high crime rates and slow police response.
 ![Hotspots](https://github.com/prashanthvaditha/EmergencyResponseBoston/blob/main/Hotspots.gif)
   

