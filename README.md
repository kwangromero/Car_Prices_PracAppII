# Github link
Link to github: https://github.com/kwangromero/Car_Prices_PracAppII.git

#Github repository description
Includes a Jupyter Notebook that includes information on how a dataset containing description of used cars (i.e., year, manufacturer, model, cylinders, fuel type, 
transmission, drive, car type, paint color, condition, title status, state/region car is issued in) can be used to predict used car prices. The dataset 
(vehicles.csv zipped into a zip file: vehicles.zip) is also included here.

# Summary of findings:
Used car prices vary from state-to-state and region-to-region. It is important to predict a used car's price from data that is from the same region as the used car in 
question.
To determine a used car's sale price, it is important to first note the region/state the car is bein sold. Below, I will use different regions of CA as an example:
If the car is from a populated area like SF bay area,CA, then a high odometer reading will decrease the price of the used car but features that would maximize the 
price of a used car are when:
•	drive = 4wd
•	fuel = diesel
•	year = 2021
•	condition = new

If the car is from a medium populated area like Gold Country-Modesto-Imperial County, CA, then the car's model, transmission, type, year, and manufacturer become 
important factors in determining a used car's price. A used car's price can be maximized if:
•	the transmission is neither automatic nor manual
•	year = 2021
•	type = other
•	manufacturer = Porsche
•	model = el camino

If the car is from a low populated area like San Luis Obispo-Monterey Bay-Siskiyou County, CA, then a high odometer reading will decrease the price of the used car 
but features that would increase the price of the car is if:
•	year = 2021
•	model = Benz
•	drive = 4wd
•	fuel = other

# next steps and recommendations
From the above information, one can see that the number one most important feature to consider, no matter which region/state the car is sold in, is the year of the 
car. Because price is more correlated to the dataset features in the low-populated dataset than in the medium/higher populated dataset, to improve the model for 
used-car price prediction in more populated regions, information of other features need to be recorded, specifically features that are valued more by residents of 
higher populated regions.

