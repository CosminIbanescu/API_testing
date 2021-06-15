# API_testing

Below are some basic API testing using the 5 Day/3 Hour Forecast API provided by openweathermap.org according to the API documentation. 

---------------------

**Title**: 
Created an api request to obtain the New Yor city temperature in celsius grades. 

**Description:** 
The endpoint is formed using two parameters. Parameters are q and units. The q parameter is specific to the city name and units parameter is used for temperature value. Metric is a unit of measure to display temperature in Celsius grades. 

**Parameters:** 
q=NewYork, units=metric. 

**Endpoint:** api.openweathermap.org/data/2.5/forecast?q=NewYork&appid=2cb2be7f539217809ca133c4f9260046&units=metric

---------------------

**Title**: 
Created an api request to obtain the New York city temperature in celsius grades by geographic coordonates. 

**Description:** 
The endpoint is formed using three parameters according to the API documentation. Parameters are: lat for latitude, lon for longitude and metric. The lat and lon parameters specify the city coordonates (New York) and units parameter is used for temperature value. Metric is a unit of measure to display temperature in Celsius grades. 

**Parameters:** 
lat = 43, lon=  -75, units=metric.  

**Endpoint:** 
api.openweathermap.org/data/2.5/forecast?lat=43.000000&lon=-75.000000&appid=2cb2be7f539217809ca133c4f9260046&units=metric

---------------------

**Title**: 
Created an api request to obtain the New York city temperature in celsius grades by geographic coordonates. 

**Description:** 
The endpoint is formed using two parameters according to the API documentation. Parameters are: zip and metric. The zip paramater is used to specify the city by zipcode. and units parameter is used for temperature value. Metric is a unit of measure to display temperature in Celsius grades. 

**Parameters and values:** 
zip = 10001, units=metic.   

**Endpoint:** 
api.openweathermap.org/data/2.5/forecast?zip=10001&appid=2cb2be7f539217809ca133c4f9260046&units=metric

---------------------
