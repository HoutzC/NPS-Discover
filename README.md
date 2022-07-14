# NPS Discover Dashboard
![image](https://user-images.githubusercontent.com/109249712/178908416-06a74339-6bc5-4e6d-9e4a-8756254b42ce.jpeg)

A fully functional powerbi report that collects data from the National Park Service (NPS) providing insights into visitation and economic trends of national park resources over the past 20 years.

# Description
This project was developed based on my passion for parks and outdoor recreation. Once I stumbled across the large amount of public data the NPS had collected over the years I saw an opportunity to further develop my skills and understanding of data engineering by applying a variety of tools and resources to see what I could do with the data.

As this is is an exhibition, the project was intentionally designed to be overly complex by incorporating a variety of tools and expertise that may not necessarily be required (cloud storage, novypro publishing, etc.)

# Architecture
![image](https://user-images.githubusercontent.com/109249712/178908872-62bb99b3-0245-4ace-8668-cff685d8619f.jpeg)

1) Data is compiled
2) Data is uploaded into an S3 bucket for object storage
3) Redshift database is established and deployed
4) Redshift is connected to Powerbi
5) Finalized Powerbi report is published

# End Product
![image](https://user-images.githubusercontent.com/109249712/178909829-6394e133-cc81-43fc-a408-f77f13013f32.jpeg)

The final product is an interactive BI report that visualizes 20 years of national park data to help understand the economic impact of resources managed by the National Park Service. 

Key features of the dashboard:
- A UX designed to deliver key KPI's and visuals with a premium product experience
- Simple and intuitive navigation panels to quickly move through the tool
- Auto scaling map using spacial data uploaded to mapbox to generate park boundaries
- Dynamic badges, icons, and images based on user selected filters to quickly convey key information
- Dynamic web links to relevent resources based on user filter selections
- Dynamic smart text to quickly summarize data for easy digestion and messaging based on filters
- Toggle buttons to increase report functionality and alleviate congestion
- Help menu for simple new user support
- Excel data export (implemented but not active/available in the publish to web environment to lower project costs)

Interact with the final product [here](https://www.novypro.com/project/nps-discover)!
> Note: Final Report is sourcing data from a static CSV file as the database was terminated upon project completion to minimize costs.
