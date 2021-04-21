### Analysis Objective
As the spread of Covid-19 in NY,the NYC Department of Health and Mental Hygiene(NYC DOHMH) plans to provide some resources such as free masks, sanitizers and booklets with health guidance in subway stations to protect the public's health against Covid. 
* Visualize the trends of Covid-19 cases in NY and by boroughs.
* Analyze the correlations between subway usages and the number of Covid cases in NY and by boroughs.

### Client Organization
 NYC Department of Health and Mental Hygiene(NYC DOHMH)

### Data Description
The following datasets will be used for the analysis:
| Dataset | Link | Data Description |
| --- | --- | --- |
| data-by-day | https://github.com/nychealth/coronavirus-data/tree/master/trends | This dataset contains daily Covid trend data by boroughs |
| turnstile_xxxxxx|  http://web.mta.info/developers/turnstile.html | Weekly turnstile usage data |
| NY Subway Geospatial Data| https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49 | Geo information of subway stations in NY |

The features that will be included in the analysis:
 * Weekly Covid cases by boroughs from 2020-01-01 to 2021-03-31
 * Weekly turnstile entries by borough from 2020-01-01 to 2021-03-31

### Tools
* Python3
* SQLite

### MVP Goal
Observe whether there's any correlation between the subway usages and the COVID cases in NYC and by boroughs.


