## Project 3 - DATA VISUALIZATION  OF FORD GO-BIKE SYSTEM

### Introduction

This dataset provides information about individual rides made in a bike-sharing system in the San Francisco Bay Area. The dataset has 183412 rows and 16 columns

The project is divided into four stages:
- [Prelimary Investigations](#investigation)
- [Data Wrangling](#wrangling)
- [Feature Engineering](#engineering)
- [Univariate Data Analysis](#univariate)
- [Bivariate Data Analysis](#bivariate)
- [Multivariate Data Analysis](#multivariate)


### <a id="investigating">Prelimary Investigation</a>
In the prelimary process, I used the ```df.isnull().sum()``` to determine the number of missing values in the dataset. There were mssing values in  in start_station_id, start_station_name, member_birth_date, member_year, and member_gender.

Also, there were no duplicated values in the dataset.

### <a id="wrangling">Data Wrangling</a>
I replaced the missing values with the  mode of the dataset.
I converted the following :
```start_time```  and ```end_time``` into datetime.

```start_station_id```,```end_station``` and ```bike_id``` to strings.

 ```user_type```  and ```member_gender``` to category.

```duation_sec``` into ```duration_min```.

I also calculated the recent ages of the user by using the code: ```df['member_age'] = 2021 - df['member_birth_year']```

Finally, I separated the   ```start_time``` into 
### <a id="engineering">Feature Engineering</a>


### <a id="univariate">Univariate Exploratory Data Analysis</a>

### <a id="bivariate">Bivariate Exploratory Data Analysis</a>


### <a id="multivariate">Multivariate Exploratory Data Analysis</a>