# plotly_challenge: Interactive Visualizations
## Biodiversity found in bellybutton

![p4wLqwS9uXF6ko9BXKLhBS](https://user-images.githubusercontent.com/62350232/91501765-fbc03f80-e88b-11ea-82ed-6227c8983d12.jpg)


The analysis of the dataset shows that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare. These microspecies are found in most people and the amount varies depending of the cleanliness of the person. 

## Procedure
1. Used d3.js to read the given data and create a dropdown function with the IDs of every participant of this research study. As well as the demographic infromation of the participant.
![readme](https://user-images.githubusercontent.com/62350232/91502467-bc92ee00-e88d-11ea-9ffb-c9f4a8989b6a.PNG)

2. Bar chart displaying the top 10 OTUs found in the selected ID sample
![readme1](https://user-images.githubusercontent.com/62350232/91502745-75592d00-e88e-11ea-875a-aa816e294a2f.PNG)

3. Bubble chart displaying the OTUs that populate the selected sample. 
![readme2](https://user-images.githubusercontent.com/62350232/91503281-b0a82b80-e88f-11ea-92e5-55fb00bcae4c.PNG)

4. (Bonus) Gauge chart displaying the frequency of belly button cleanliness; which affects the kind and amount of OTUs found in the samples. 
![readme4](https://user-images.githubusercontent.com/62350232/91503434-11376880-e890-11ea-9a88-ddb299877844.PNG)

5. Each time a new ID sample is selected, it updates every chart according to the information belonging to that sample ID. 
