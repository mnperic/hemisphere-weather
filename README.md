# Global weather patterns based on hemisphere – Temperature, Humidity, Cloudiness, Wind Speed
A study of global cities and weather patterns based on temperature, humidity, cloudiness and wind speed.

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/globe.png" alt="globe"/>
</p>

## Analysis
### Temperature (C) vs. Latitude

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/lat_temp.png" alt="lat_temp"/>
</p>

The above plot demonstrates the relationship between latitude and temperature (C). It shows a temperature increase as one approaches the equator (latitude 0).

### Humidity (%) vs. Latitude

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/lat_humidity.png" alt="lat_humidity"/>
</p>

The above plot demonstrates the relationship between latitude and humidity (%), showing a minimal or null correlation between the two.

### Cloudiness (%) vs. Latitude

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/lat_cloudiness.png" alt="lat_cloudiness"/>
</p>

The above plot demonstrates the relationship between latitude and cloudiness, once again showing a minimal or null correlation between the two.

### Wind Speed (kph) vs. Latitude

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/lat_wind_speed.png" alt="lat_wind_speed"/>
</p>

The above plot demonstrates the relationship between latitude and wind speed (kph). It shows wind speeds are generally greater further away from the equator (latitude 0).

## Linear Regression
### Max Temperature vs. Latitude
#### Northern Hemisphere

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/nh_lat_temp_regression.png" alt="nh_lat_temp_regression"/>
</p>

#### Southern Hemisphere

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/sh_lat_temp_regression.png" alt="sh_lat_temp_regression"/>
</p>

As demonstrated in the plots above, both the Northern and Southern hemispheres show the same inverse relationship between latitude and temperature. As one gets closer to the equator (latitude 0), the higher the temperature gets. There is also a strong correlation for both hemishperes, but the Northern Hemisphere seems to have an almost 1:1 relationship between temperature and latitude.

### Humidity (%) vs. Latitude
#### Northern Hemisphere

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/nh_lat_humidity_regression.png" alt="nh_lat_humidity_regression"/>
</p>

#### Southern Hemisphere

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/sh_lat_humidity_regression.png" alt="sh_lat_humidity_regression"/>
</p>

As demonstrated in the plots above, the correlation between humidity and latitude appears to be minimal. However, there appears to be a slight positive correlation in the Northern hemisphere and a slight negative correlation in the Southern hemisphere; meaning in the Northern hemisphere as you get further away from the equator (latitude 0) humidity increases, and in the Southern Hemisphere it decreases as you get further away from the equator. This may be examined in a future investigation of Northern and Southern poles (Arctic vs. Antarctica).

### Cloudiness (%) vs. Latitude
#### Northern Hemisphere

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/nh_lat_cloud_regression.png" alt="nh_lat_cloud_regression"/>
</p>

#### Southern Hemisphere

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/sh_lat_cloud_regression.png" alt="sh_lat_cloud_regression"/>
</p>

As demonstrated in the plots above, the correlation between cloudiness and latitude appears to be minimal. However, according to the linear regression, one may observe a slight positive correlation in the Northern hemisphere, and a strong negative correlation in the Southern hemisphere. In the Southern hemisphere, it shows that the further you are from the equator (latitude 0) the less cloudy it is.

### Wind Speed (kph) vs. Latitude
#### Northern Hemisphere

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/nh_lat_wind_regression.png" alt="nh_lat_wind_regression"/>
</p>

#### Southern Hemisphere

<p align="center">
  <img src="https://github.com/mnperic/hemisphere-weather/blob/main/Images/sh_lat_wind_regression.png" alt="sh_lat_wind_regression"/>
</p>

As demonstrated in the plots above, there is a strong correlation between wind speed and latitude in both hemispheres. However, a linear regresion demonstrates a much lower correlation than it appears. A definitive correlation in both hemispheres is observed, in that the further one is from the equator (latitude 0), the higher the wind speeds are, but the slope of the regression line is much less drastic than expected.
