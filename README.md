# python-api-challenge
Module 6 challenge

Please see the attached documents in the WeatherPy folders to view the code and resources.

This challenge was to demonstrate the used of Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?" as well as to use Jupyter notebooks, the geoViews Python library, and the Geoapify API and the data collected from the WeatherPy to plan future vacations by searching for specific weather criteria and findng a near by hotel. 

## Part 1: WeatherPy
What is the weather like as we approach the equator?

Through this section a variety of cities accross the globe were selected and then a number of elements were examined to determine what the weather is like as we approach the equator by examining trends between the Norhtern and Southern hemisphere. 

Northern Hemisphere Results:

![Norhtern Temp](https://user-images.githubusercontent.com/120147552/216836546-0d5122af-19a3-402c-959b-ac989eebc61b.png)

![Northern Hum](https://user-images.githubusercontent.com/120147552/216836553-9c96fd38-6673-494e-ba0e-e90cfb3827ba.png)

![northern wind](https://user-images.githubusercontent.com/120147552/216836556-2df37425-1fa1-454a-9a27-569484b98e8a.png)

![nothern cloud](https://user-images.githubusercontent.com/120147552/216836560-c99babcb-9640-4b5d-b026-0c3752d8514e.png)

Southern Hemisphere Results:

![Southern Temp](https://user-images.githubusercontent.com/120147552/216836572-92243181-5366-4ef8-8eda-9c6fd122fee8.png)

![southern Hum](https://user-images.githubusercontent.com/120147552/216836576-dc946e22-d2c0-4d88-add7-fe2613e86892.png)

![southern wind](https://user-images.githubusercontent.com/120147552/216836589-51943ddf-31f9-433a-b3c4-906c451b719f.png)

![Southern cloud](https://user-images.githubusercontent.com/120147552/216836591-7a48e3e7-ca0c-42ee-b59a-fcd3cde89bd6.png)

 
 For the Northern Hemisphere, there is a negative correlation between Max Temperature and Latitude; meaning that the greater the Latitude (further from the equator) the lower the Max Temperature is. For the Sothern Hemisphere, there is a positve correlation between Max Temperature and Latitude; meaning that the greater the Latitude (closer the the equator) the higher the Max Temperature is. Other factors do not appear to offer a strong enough correlation and it appears that other factors my be affecting there results other than Latitude.

## Part 2: VacationPy
Plan future vacations by searching for specific weather criteria and findng a near by hotel.

Initial search for vacation spots without searching based on specified criteria, resulted in providing us with an asortment of random locations to vacation at:

![vacation starting point](https://user-images.githubusercontent.com/120147552/216836994-af1faa9e-a30e-45fc-8b87-8b976ce4db19.png)

Desired weather conditions for vacation location:
* Max Temp (C) 18 > & < 30
* Wind Speed < 7
* Cloudiness < 25

Locations matching the desired weather conditions and that have a hotel within 10,000 meters:

![vacations with hotels](https://user-images.githubusercontent.com/120147552/216837796-73359ca6-c3a8-4aca-92c4-fc5efa317180.png)


