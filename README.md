# **Toronto Urban Heat Island Analysis**

## **Assessing the Relationship Between Median Income and Land Surface Temperature**
---
**Author**: Sebastian Brubaker  
**Date**: May 2025

---

### **Background–Why Identifying and Mitigating Urban Heat Islands Matters**
**The Urban Heat Island (UHI) effect** is a phenomenon where urban environments become significantly warmer than their surroundings and retain high temperatures overnight due to building materials, lack of vegetation and human activity.

UHIs pose **significant risk** to public health, energy consumption, as well as contributing to environmental degradation in urban areas. It has been shown that **socioeconomically disadvantaged areas are disproportionately affected by UHIs** (Sarricolea et al., 2022). Additionally, these areas have been or are currently subject to discrimination. Furthermore, the UHI effect is exacerbated by the factors creating the socioeconomic disadvantage, such as limited access to healthcare, low income, limited access to greenspace, limited access to air conditioning, etc.

### **Overview**
**This geospatial analysis assesses if there is a statistically significant correlation between median income and land surface temperature (LST) in the City of Toronto.** It is suspected that as income decreases LST increases. The median income and neighbourhood boundaries datasets are retrieved from the City of Toronto’s Open Data Portal and the LST data will be derived from remotely sensed imagery from Landsat 8-9’s Operational Land Imager and Thermal Infrared Sensor. LST will be summarized by neighbourhood using zonal statistics. Bivariate analysis will be performed between median income and the appropriate LST zonal statistics.