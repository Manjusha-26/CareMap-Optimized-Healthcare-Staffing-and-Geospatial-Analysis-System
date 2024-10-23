# CareMap-Optimized-Healthcare-Staffing-and-Geospatial-Analysis-System
## Project Overview:
This project focuses on optimizing the allocation of healthcare staff across different facilities within a healthcare network. Uneven distribution of resources can lead to inefficiencies such as overburdened staff in some areas while others remain underutilized. The project aims to achieve a balanced staff-to-patient ratio across all facilities, ensuring optimal healthcare service delivery.

Additionally, the project calculates geographic distances between facilities to aid in decision-making related to resource sharing, staff collaboration, and patient transfers. We use Python libraries such as Pandas, Geopy, and Folium to gather, manipulate, and visualize the data.

## Key Features:
- **Data Gathering**: Extracts population data from specific Washington state zip codes and merges it with healthcare facility data.
- **Data Analysis**: Calculates healthcare worker-to-patient ratios and determines optimal staff distribution based on the population served by each facility.
- **Distance Calculation**: Measures the geographic distance between healthcare facilities to aid in logistical planning.
- **Data Visualization**: Uses Folium maps to visualize the location of facilities and the distances between them.

## Steps Involved:
1. **Data Gathering**: Web scraping to retrieve population data by zip code from an online source.
2. **Data Understanding & Cleaning**: Perform data inspection, cleaning, and preparation to ensure accuracy and consistency for analysis.
3. **Data Manipulation**: Merge facility data with population data, calculate current staff-to-patient ratios, and redistribute staff based on population needs.
4. **Optimization**: Implement algorithms to allocate healthcare workers proportionally to population demands.
5. **Distance Calculation**: Calculate distances between facilities and visualize results on interactive maps.
6. **Mapping and Visualization**: Display healthcare facilities and inter-facility distances using Folium for enhanced geographical insights.

## Technologies Used:
- **Python**: Core programming language for data manipulation and calculations.
- **Pandas**: Data manipulation and analysis.
- **Geopy**: Geolocation and distance calculations between facilities.
- **Folium**: Interactive map visualization.
- **BeautifulSoup**: Web scraping for data collection.

## Conclusion:
By redistributing healthcare staff based on population needs and mapping out the geographic distances between facilities, this project provides actionable insights for improving healthcare service delivery. The interactive maps and data analysis enable decision-makers to efficiently allocate resources and manage inter-facility collaboration.
