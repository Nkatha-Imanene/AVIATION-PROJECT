# AVIATION-PROJECT
# Aviation Accident Data Analysis Project

## Project Description

This project involves a comprehensive data analysis of aviation accidents using data from the National Transportation Safety Board (NTSB). The dataset includes civil aviation accidents and selected incidents in the United States and international waters from 1962 to 2023. The goal of this analysis is to recommend an aircraft manufacturer in the private aircraft space and the commercial aircraft space for my company which is seeking to venture into the aviation industry. The primary focus is to identify aircraft with the lowest risk to ensure a safe and sustainable business endeavor.

## Data Description

The dataset used for this analysis, was the aviation accidents dataset from kaggle. It contains the following columns:

- `Event_Id`: Unique identifier for the event
- `Investigation_Type`: Type of investigation (Accident/Incident)
- `Accident_Number`: Accident number
- `Event_Date`: Date of the event
- `Location`: Location of the event
- `Country`: Country where the event occurred
- `Airport_Name`: Name of the airport (if applicable)
- `Injury_Severity`: Severity of injuries (e.g., Fatal, Serious, Minor, None)
- `Aircraft_Damage`: Extent of aircraft damage
- `Registration_Number`: Aircraft registration number
- `Make`: Manufacturer of the aircraft
- `Model`: Model of the aircraft
- `Number_Of_Engines`: Number of engines on the aircraft
- `Engine_Type`: Type of engine (e.g., Jet, Piston)
- `Purpose_Of_Flight`: Purpose of the flight (e.g., Commercial, Private, Training)
- `Total_Fatal_Injuries`: Total number of fatal injuries
- `Total_Serious_Injuries`: Total number of serious injuries
- `Total_Minor_Injuries`: Total number of minor injuries
- `Total_Uninjured`: Total number of uninjured individuals
- `Weather_Condition`: Weather conditions at the time of the event (e.g., VMC, IMC, Unknown)
- `Broad_Phase_Of_Flight`: Phase of flight during the event (e.g., Takeoff, Landing, Cruise)
- `Publication_Date`: Date of publication of the report
- `Total_Passengers`: Total number of passengers on board
- `Fatal_Injury_Number`: Number of fatal injuries
- `Uninjured_Number`: Number of uninjured individuals

## Analysis Steps

1. **Data Preparation**
   - Load and clean the data: drop unnecessary columns, identified & handle missing values, and ensure proper formatting.
   - Filter data for specific manufacturers (Top 10 manufacturers: Boeing, Airbus, Bombardier,Cessna, Embraer, Gulfstream,Pilatus, Hawker , Dassault, Lockheed).

2. **Key Metrics Calculation**
   - Calculate total accidents, fatal accidents, serious accidents, minor accidents, and uninjured incidents for top 10 manufacturers.
   - Analyze injury severity distribution for manufacturers.
   - For the 2 recommended manufacturers:
   - Assess engine reliability by examining incidents related to different engine types.
   - Evaluate the impact of weather conditions on accident rates.
     

3. **Visualizations**
   - Create visualizations in matplot to support the analysis and recommendations:
     - Staked bar chart : injury rate by make
     - Stalked bar chart : Mean uninjured & fatality rate by make
   
   - Create visualizations in Tableau to support the analysis and recommendations:
     - Bar Chart: avg fatal injuries by make
     - Bar Chart: avg serious injuries by make
     - Bar Chart: avg minor injuries by make
     - Bar Chart: avg uninjured by make
     - Bubble Chart: Engine Type vs. Number of Incidents
     - Stalked Bars: Phase of flight & weather by No. of accidents
     - Stalked Bars: Purpose of flight by No of accidents
     - Bar Chart : Weather conditions by No of accidents
     - Bar Chart : Phase of flight by accidents
     - Dual Combination: No. of accidents & Total fatalities over time
     
     - Injury - Severity Dashboard
     - Engine type & Weather dashboard

## Results and Recommendations

### Gulfstream (Private Aircraft Sector)
- **Safety Record:** Gulfstream has a lower number of total accidents compared to other private aircraft manufacturers.
- **Injury Severity:** Higher proportion of minor or uninjured incidents, indicating effective safety measures.
- **Engine Reliability:** Fewer engine-related incidents, reflecting robust engine performance and maintenance protocols.
- **Weather Resilience:** Better handling of adverse weather conditions, resulting in fewer weather-related accidents.

### Boeing (Commercial Aircraft Sector)
- **Safety Record:** Boeing maintains a relatively low accident rate despite a high volume of operations.
- **Injury Severity:** Lower fatality rate compared to other commercial aircraft manufacturers, showcasing effective safety features.

Based on the analysis, **Gulfstream** is recommended for the private aircraft sector due to its excellent safety record, reliable engine performance, and better handling of adverse weather conditions. For the commercial aircraft sector, **Boeing** is recommended because of its low accident rate relative to its volume of operations and high uninjured passengers rate.
## Tableau Dashboards

To further explore the data and visualizations supporting these recommendations, visit the [Tableau Dashboards](https://public.tableau.com/views/Imanene-Phase1-project-InjuryseverityDashboard/InjuryseverityDashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link) & [Tableau Dashboards](https://public.tableau.com/views/Imanene-Phase1-project-enginetypeweatherDashboard/EnginetypeWeatherdashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- National Transportation Safety Board (NTSB) for providing the dataset.
- Tableau for data visualization tools.
- [Maureen Nkatha Imanene] for data analysis and recommendations.
