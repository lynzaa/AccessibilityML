**Exploring Accessibility for Disabled People in the City of Melbourne**

**Authored by**: Liny Jose Alias

**Duration**: 90 mins

**Level**: Intermediate

**Pre-requisite Skills**: Python, Data Visualization, Data Wrangling, Machine Learning Models,Deep Learning

**Scenario**
As a healthcare worker, I would like to know the nearest public toilets with facilities and accessibility for my disabled patients.

As a healthcare worker, i would like to know the areas friendly for visually impaired people.

***Project Objective, Overview & Research***

This use case aims to evaluate the accessibility of urban infrastructure for disabled individuals in the City of Melbourne. By analyzing datasets that include tactile ground surface indicators (TGSI), public toilets, and train station accessibility information, the City of Melbourne can identify areas where accessibility improvements are needed. The goal is to enhance the inclusiveness and navigability of the city for people with disabilities.

Dataset 1:
https://data.melbourne.vic.gov.au/explore/dataset/tactile-ground-surface-indicator/information/
This dataset contains tactile ground surface indicators(TGSI) that are located within the central business district of the City of Melbourne.
TGSI are used to help vision impaired people navigate the urban environment to avoid hazards.

Dataset 2:
https://data.melbourne.vic.gov.au/explore/dataset/public-toilets/information/
Public toilets known about or operated by the council. 

Dataset 3:
https://data.melbourne.vic.gov.au/explore/dataset/metro-train-stations-with-accessibility-information/information/
This data contains locations of train stations and their accessibility information, such as hearing aid information.

## Executive Summary

This project presents the findings of a data-driven analysis aimed at assessing and improving accessibility features for disabled individuals in the City of Melbourne. By analyzing datasets that include tactile ground surface indicators (TGSI), public toilets, and metro train stations' accessibility information, we identified several areas where infrastructure improvements are needed. These enhancements will make the city more inclusive and navigable for individuals with disabilities, particularly those who are visually impaired or physically disabled.

### Key Insights:

**Tactile Ground Surface Indicators (TGSI):**
The analysis revealed 10 high-priority locations that require improvements in TGSI infrastructure to support the visually impaired. All these locations had only one TGSI feature, suggesting a lack of comprehensive support for vision-impaired navigation. The most critical areas include intersections on Lonsdale Street, Bourke Street, Elizabeth Street, and Flinders Street, where increased TGSI coverage would improve safety and mobility.

**Public Toilets:**
The availability of wheelchair-accessible toilets was another key focus. The data analysis highlighted 5 top-performing public toilet locations with the most comprehensive facilities, ensuring accessibility for both male, female, and wheelchair users. However, 5 locations were found to have inadequate facilities, with minimal to no wheelchair accessibility, particularly in Ron Barassi Senior Park Pavilion and Fawkner Park.

**Metro Train Stations:**
Train station accessibility features were also assessed, focusing on key components such as hearing loops, lifts, and real-time passenger information display systems (PIDS). The analysis identified the top 10 stations with the most comprehensive accessibility features, ensuring a fully accessible transit experience for disabled commuters. Conversely, 5 stations were flagged as having poor accessibility, with no hearing loops, lifts, and outdated dot matrix PIDS. Immediate improvements are recommended for stations such as Alphington, Regent, and Patterson to ensure all passengers, regardless of disability, can comfortably use the city's train network.

### Execution Modality

In addition to the exploratory analysis, a predictive machine learning (ML) model was developed to forecast accessibility scores across various areas in the City of Melbourne. This model was trained on features such as TGSI coverage, public toilet accessibility, and train station facilities. The model allowed for a data-driven approach in identifying areas most in need of improvement.

Furthermore, facility scores were calculated for public toilets and train stations based on the availability of accessibility features such as wheelchair access, hearing loops, and lifts. These scores provided a quantifiable measure to prioritize locations for infrastructure upgrades, enabling a more efficient allocation of resources to enhance urban accessibility.

An interactive map highlighting locations with high, medium and low accessibility features.

### Findings:

#### **Top 10 Locations Requiring TGSI Improvements:**
The following locations were identified as requiring urgent upgrades in tactile ground surface indicators (TGSI) for visually impaired individuals. All locations had only one TGSI feature, indicating a need for improvement:
1. **Lonsdale Street / Russell Street** (Lat: -37.810998, Lon: 144.967115)
2. **Bourke Street / Elizabeth Street** (Lat: -37.813282, Lon: 144.962838)
3. **Bourke Street / Elizabeth Street** (Lat: -37.813354, Lon: 144.962620)
4. **Bourke Street / Elizabeth Street** (Lat: -37.814052, Lon: 144.963247)
5. **Bourke Street / Elizabeth Street** (Lat: -37.814152, Lon: 144.962995)
6. **Bourke Street / Elizabeth Street** (Lat: -37.814349, Lon: 144.963326)
7. **Elizabeth Street / Collins Street** (Lat: -37.816105, Lon: 144.963824)
8. **Elizabeth Street / Collins Street** (Lat: -37.816413, Lon: 144.963978)
9. **Elizabeth Street / Flinders Street** (Lat: -37.818061, Lon: 144.964732)
10. **Swanston Street / Little Lonsdale Street** (Lat: -37.810504, Lon: 144.964342)

#### **Public Toilets – Facilities Overview:**

**Top 5 Locations with Most Facilities:**
The following public toilets had the most comprehensive facilities, including male, female, and wheelchair accessibility:
1. **Victoria Harbour, Shed 2 (North Wharf Road)**
2. **Point Park (Point Park Crescent)**
3. **Fitzroy Gardens (Grey Street)**
4. **Franklin Street (Off-street parking)**
5. **Royal Park (Flemington Road)**

**5 Locations with Least Facilities:**
These public toilets were identified as having insufficient facilities, particularly for disabled individuals:
1. **Ron Barassi Senior Park Pavilion** (0 female, 0 male, 0 wheelchair-accessible facilities)
2. **Fawkner Park (Northern Pavilion)** (2 female, 1 male, 1 wheelchair-accessible facility)
3. **Swanston Street (Lincoln Square)** (2 female, 1 male, 1 wheelchair-accessible facility)
4. **Queensberry Street (between Cardigan and Leicester Street)** (1 female, 2 male, 1 wheelchair-accessible facility)
5. **Gordon Reserve (74-108 Spring Street)** (2 female, 1 male, 1 wheelchair-accessible facility)

#### **Top 10 Train Stations by Accessibility Features:**
These stations had the most comprehensive accessibility features, including hearing loops, lifts, and real-time passenger information display systems (PIDS):
1. **Southland**
2. **Mckinnon**
3. **St Albans**
4. **Gardiner**
5. **Parliament**
6. **Melbourne Central**
7. **Heatherdale**
8. **Flagstaff**
9. **Ginifer**
10. **Bentleigh**

**5 Worst Stations Requiring Improvement:**
The following stations had the least accessibility features, requiring significant upgrades:
1. **Alphington** – No hearing loop, no lift, outdated dot matrix PIDS.
2. **Regent** – No hearing loop, no lift, outdated dot matrix PIDS.
3. **Patterson** – No hearing loop, no lift, outdated dot matrix PIDS.
4. **Upper Ferntree Gully** – No hearing loop, no lift, outdated dot matrix PIDS.
5. **Thornbury** – No hearing loop, no lift, outdated dot matrix PIDS.



### **Suggestions for Improvement**

**Tactile Ground Surface Indicators (TGSI):**
- Upgrade TGSI infrastructure in highly trafficked intersections like Bourke Street, Elizabeth Street, and Flinders Street to ensure accessibility for vision-impaired individuals.

**Public Toilets:**
- Increase the number of wheelchair-accessible toilets in locations like Ron Barassi Senior Park Pavilion, Fawkner Park, and Queensberry Street to ensure inclusiveness for physically disabled users.

**Train Stations:**
- Install hearing loops and lifts in stations like Alphington, Regent, Patterson, Upper Ferntree Gully, and Thornbury to enhance accessibility for disabled commuters. These stations should also upgrade their PIDS to modern systems that provide clear, real-time information.



### **Conclusion**
This analysis identified several locations in the City of Melbourne that require urgent improvements in accessibility infrastructure. By focusing on enhancing TGSI coverage, improving public toilet facilities, and upgrading accessibility features at metro train stations, the City of Melbourne can create a more inclusive urban environment for disabled individuals. Prioritizing accessibility enhancements will benefit the city's disabled population, particularly those with vision and mobility impairments.