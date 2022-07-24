# PyBer_Analysis

1. Overview of the analysis: 
    - From our previous project and submitted analysis to the PyBer CEO with our client Omar,  the CEO has has given us and Omar a brand new objective and project overview. Using our Python skills and knowledge of Pandas, we created a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, we also created a multiple-line graph that shows the total weekly fares for each city type. Finally, we have a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

2. Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
    - Summary DataFrame:
      - <img width="925" alt="Screen Shot 2022-07-24 at 2 30 27 PM" src="https://user-images.githubusercontent.com/107281474/180666659-7158ac56-fc44-44c2-b847-3c28813cb814.png">
      - <img width="911" alt="Screen Shot 2022-07-24 at 2 30 47 PM" src="https://user-images.githubusercontent.com/107281474/180666666-ca8b31fa-a883-4800-811a-27fd73a43b47.png">
      - <img width="925" alt="Screen Shot 2022-07-24 at 2 31 05 PM" src="https://user-images.githubusercontent.com/107281474/180666673-26aea8fe-8168-473b-8422-e7019a8c05f6.png">
      - <img width="920" alt="Screen Shot 2022-07-24 at 2 31 29 PM" src="https://user-images.githubusercontent.com/107281474/180666679-11326f2b-db5d-4fc3-8895-7669bc5a401f.png">
    - After getting the total amount and average fare per ride and drivers based on city type, we converted the datasets by using the groupby() function, and used the fares per ride and fare per driver averages that resulting and the creation of the pyber_summary_df DataFrame by city type:
      - <img width="829" alt="Screen Shot 2022-07-24 at 2 36 12 PM" src="https://user-images.githubusercontent.com/107281474/180666817-28d5bbea-1550-48f9-9fef-e7123878309f.png">
    - From the summary DataFrame for PyBer, urban city type had significantly more total drivers that listed total rides for PyBer customers. This had a a strong effect on the average fare per ride and also per driver. In addition, for urban type drivers, they had lower average fares per ride due to the high volume and density of the population and earned less than rural type drivers. 
    - From their urban type counterparts, the rural drivers had the highest average fare per driver while also having the least number of total drivers due to the high travel and mileage demand. 
    - Total Fare by City Type:
    - With the creation of the PyBer Summary DataFrame for the analysis, the data was then exported and pivoted into a new visual DataFrame which was then grouped by weeks instead of months to then illustrate PyBer's total fares by city type (Urban, Suburban, Rural). 
      - <img width="872" alt="Screen Shot 2022-07-24 at 2 44 32 PM" src="https://user-images.githubusercontent.com/107281474/180667033-5fbc6a2a-4fa4-423d-976d-c78f88d3f450.png">
    - All of PyBer's city types start to rise gradually and the month continues throughout the year. For the Suburban city type, there was a sharp decline as March began whereas the other two city types there was a gradual declination. 
    - For the Urban city type there was a sharp fluctuation from March to April and Suburban city types saw a sharp increase towards the end of the month most likey to seasonal events or changes such as Spring break holidays. 

4. Summary: 
    - Based on the results, we provided three business recommendations to the CEO for addressing any disparities among the city types:
      - 1. Pyber should invest in Metrics & Analytics for traffic volume amongst desireable and highly populated urban and suburban areas. From the analysis it seems that certain seasons have a slight correlation on PyBer demand. If enacted correctly on SEO and advertisement on key dates, PyBer can optimize on reaching a larger audience and brand/service awareness.
      - 2. From the Summary DataFrame for PyBer, since Urban city type areas are more compact and have more complex traveling routes, this can disparage consumers to use alterantive methods that can affect a lower average fare per ride, while Rural city types are more widespread and cover larger distance. PyBer should incorporate and R&D to traffic data and mileage data.
      - 2. Since there are more total drivers than total rides in the Urban and Suburban city types, the Urban and Suburban drivers may have more competition to effectively market and support themselves. PyBer may want to consider investing in  PyBer rider's employee programs to  increase retention rates. 

