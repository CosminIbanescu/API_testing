# API_testing

Below are some basic API testing using the 5 Day/3 Hour Forecast API provided by openweathermap.org according to the API documentation. 

---------------------

**Title**:

Created an api request to obtain the New York city temperature in celsius grades by zip code and display the API response in romanian language. 

**Description:** 

The endpoint is formed using three parameters. Parameters are: zip, metric and lang. The zip paramater is used to specify the city by zip code. Units parameter is used for temperature value and metric is a unit of measure to display temperature in Celsius grades. The lang parameter is used to display API response in romanian language.  

**Parameters and values:** 

zip = 10001, units = metic, lang = ro. 

**Endpoint:** 

api.openweathermap.org/data/2.5/forecast?zip=10001&appid=2cb2be7f539217809ca133c4f9260046&units=metric&lang=ro

---------------------

**Title**: 

Created an api request to obtain the New York city temperature in celsius grades by geographic coordonates and display the API response in XML format.  

**Description:** 

The endpoint is formed using four parameters. Parameters are: lat for latitude, lon for longitude, metric, and mode. The lat and lon parameters specify the city coordonates (New York). Units parameter is used for temperature value and metric is a unit of measure to display temperature in Celsius grades. Mode parameter is used to display the API response in xml format.  

**Parameters:** 

lat = 43, lon = -75, units = metric, mode = xml.  

**Endpoint:** 

api.openweathermap.org/data/2.5/forecast?lat=43.000000&lon=-75.000000&appid=2cb2be7f539217809ca133c4f9260046&units=metric&mode=xml

---------------------

**Title**: 

Created an api request to obtain the New Yor city temperature in celsius grades. 

**Description:** 

The endpoint is formed using two parameters. Parameters are q and units. The q parameter is used to specify the city name and units parameter is used for temperature value. Metric is a unit of measure to display temperature in Celsius grades. 

**Parameters:** 

q = New York, units = metric. 

**Endpoint:** 

api.openweathermap.org/data/2.5/forecast?q=New York&appid=2cb2be7f539217809ca133c4f9260046&units=metric

---------------------
