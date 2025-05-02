# MIST4610-Project2-Group4

## Team Name: 
61608 Group 4

## Team Members (alphabetical):
1. An, Ben [@benan03](https://github.com/benan03)
2. Burt, Keegan[@keeganburt24](https://github.com/keeganburt24)
3. Cheng, Hsin [@hc83710](https://github.com/hc83710)
4. Cho, Nick [@nichooo4](https://github.com/nichooo4)
5. Shields, David [@DubNation44](https://github.com/DubNation44)

## Dataset Overview
Our chosen dataset is titled "Crime Data from 2020 to Present", and it was obtained from the Los Angeles Police Department via Data.gov. The dataset records crime incidents reported by the LAPD beginning in 2020 and is updated on a bi-weekly basis. It includes data from original paper reports, which may contain minor inaccuracies or incomplete fields due to system transitions and reporting delays.

The dataset features a variety of useful fields such as the case number (DR_NO), the date the crime occurred (DATE OCC), the geographic area where the crime took place (AREA NAME), the type of crime (Crm Cd Desc), and whether a weapon was used (Weapon Desc). Additionally, geolocation information is provided through latitude and longitude fields (LAT, LON), enabling spatial analysis of crime patterns across Los Angeles.

Through this information, we were able to analyze crime distribution and trends, examine the frequency of violent incidents, and explore how external factors—such as shifts in police funding—may have influenced overall crime rates in Los Angeles over the past five years.

## Question 1
Where should LAPD send more officers to reduce crime?

![image](https://github.com/user-attachments/assets/f698af42-4959-4e09-add2-3657cc9b3c6c)

![image](https://github.com/user-attachments/assets/3664b1c1-525c-4c03-b365-07ae19843162)


We chose to explore this question visually using a heatmap and a bar graph that illustrate the density and location of violent crimes across Los Angeles regions. The central focus of this analysis is to determine where LAPD resources—particularly patrol officers—can be deployed most effectively to reduce crime. We filtered our data to only include violent crimes such as murder, manslaughter, rape, robbery, and aggravated assault were prioritized, as these incidents have the most immediate and serious consequences for public safety. To the details section, we incuded the charge, as well as the date occured. This information can further help the LAPD to answer which crimes are most prevalent in which areas. Furthermore, our last manipulation was filtering the years, we restricted the data to only contain crimes from 2023-Present to give us the most up-to-date information.

The heatmap shows clusters of high crime density, particularly in certain central and southern areas of LA. These regions are highlighted in dark red, signaling a greater concentration of violent crime. The accompanying bar chart titled "Number of Crimes per Square Mile by Region" identifies Central LA as having the highest crime rate, followed by regions like 77th Street, Southwest, and Southeast. These visuals together provide a strong case for reallocating or increasing officer presence in these high-density zones to deter crime, respond faster, and increase community protection.

This question is important because LA has one of the highest crime rates among major U.S. cities, and efficient allocation of law enforcement is key to resource management. Understanding where violent crime is concentrated allows law enforcement to act strategically rather than reactively. Ultimately, this question helps guide smarter decisions in policing and promotes a more data-driven approach to public safety.



## Question 2
Has Defunding the Police Affected Crime in LA?

<img width="675" alt="Screenshot 2025-04-30 at 9 51 00 PM" src="https://github.com/user-attachments/assets/9f045c9c-a61d-4483-b637-28590d8961f1" />

To explore the impact of recent police budget changes, we asked: Has defunding the police affected crime in Los Angeles? This question is especially relevant given the national conversation around policing and public safety reform following 2020.

We visualized this question using a line graph created in Tableau, which displays the annual number of reported crime cases in Los Angeles from 2020 to 2024. The graph focuses on the four LAPD areas with the highest cumulative crime counts: Central, 77th Street, Pacific, and Southwest. By filtering the dataset to include only these regions and organizing the results by year, we were able to observe meaningful patterns in crime trends.

This question matters because understanding how crime rates have evolved in the wake of police budget changes can help guide future resource allocation and public safety strategies. From 2020 to 2022, crime increased significantly in each of the four areas, possibly due to reduced police presence, broader social unrest, or pandemic-related factors. However, from 2023 to 2024, we observed a sharp decline in crime rates across all regions. This reversal may reflect delayed effects of earlier reforms, adjustments in police deployment strategies, or improvements in community-based safety initiatives.

By focusing on high-crime regions and tracking these shifts over time, this analysis provides valuable insights for policymakers, law enforcement, and local communities seeking to strike a balance between public safety and social justice.

## Manipulations

(The manipulations for the first question is detailed in the previous section under question 1's graphs.)


For our second question, we used "Dr No" column to identify unique crime cases, counting them and putting them on the Rows section of the TABLEAU graph. We then put the "Year" element of "Date Occ" column to the Columns section. By doing these steps, we formed a graph that shows the increase and decrease of crime cases over the years. 

<img width="477" alt="image" src="https://github.com/user-attachments/assets/5e01e28a-16d0-42a4-8414-b1cea8a4d807" />


We also applied a few key filters to help clarify trends and focus our analysis. Specifically, we chose to include only the four LAPD divisions with the highest total crime counts: Central, 77th Street, Pacific, and Southwest, by filtering the "Area Name" column. Including all 21 areas would make the visualization cluttered and difficult to interpret, so narrowing the focus helped emphasize the areas most relevant to our research.

<img width="449" alt="image" src="https://github.com/user-attachments/assets/835e9f5c-8edc-4db5-b560-63ae93e9c03a" />


In addition, we restricted the data to crime cases reported to the time range between 2020 and 2024 by filtering the "Year" of "Date Occ" column. This allowed us to examine crime trends during a time period when discussions around police funding were most prominent. These manipulations help make the line graph cleaner and the trends more distinct, enabling us to draw more meaningful conclusions about potential shifts in crime related to police defunding.

<img width="435" alt="image" src="https://github.com/user-attachments/assets/0288c85c-6cd5-4fe3-ab19-8da66b725e0b" />



## Analysis and Results
Our analysis of LAPD crime data from 2020 to 2024 focused on identifying trends in total crime across different areas of Los Angeles, understanding why crime increased during this period, and evaluating how trends changed over time. We found that total reported crime increased significantly between 2020 and 2022, peaking in 2022 across nearly all high-crime areas, including Central, Pacific, 77th Street, and Southwest. Some areas experience slight decline in crimes from 2022 tp 2023, then from 2023 to 2024, crime declined sharply in all four regions.

This rise in crime from 2020 to 2022 can largely be explained by the social and economic disruptions caused by the COVID-19 pandemic. During this period, police resources were stretched thin, public stress and unemployment surged, and many community programs were halted—factors that are known to increase criminal activity. As society reopened in 2021 and 2022, more people returned to public spaces, increasing opportunities for certain crimes like theft and assault.

The somewhat uniform decline in crime in 2023 likely reflects a return to normalcy, increased policing, and broader social recovery. Our findings support the idea that the spike in crime was a temporary result of pandemic-related instability, and not a long-term shift. Geospatial data also revealed that high-crime neighborhoods often aligned with areas of greater population density and economic hardship, reinforcing the importance of social context in crime prevention.

Overall, our charts clearly show a consistent pattern across all four of the highest-crime areas: a steady increase in total crimes from 2020 through 2022, followed by a slight decline in 2023. The Pacific area experienced the most dramatic peak in 2022, with over 17,000 reported cases, while the other areas followed similar trends. The parallel movement in all regions suggests a general effect rather than isolated local changes. These visual trends reinforce the conclusion that external factors, like the pandemic and its aftermath as well as the defunding of the police, had a widespread impact on crime levels throughout Los Angeles.

Upon further analysis, we realized that the data in 2024 may be still incomplete to date due to LAPD's adoption of a new "Records Management System" mentioned on its webpage. It is possible that the department is still working on consolidating the new and old records for the year 2024, hence the dramatic decline of crime records for the year 2024. 

## Sources
(LAPD OpenData. Crime Data from 2020 to Present. Data.gov, updated April 19, 2025, https://catalog.data.gov/dataset/crime-data-from-2020-to-present. )
